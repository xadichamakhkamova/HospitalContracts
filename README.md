# Hospital Contracts

This repository contains **Protocol Buffers (Protobuf) definitions** and generated Go code (`genproto`) used by the **Hospital Management System** microservices.

All services (Admin Panel, Doctor Service, Nurse Service, Patient Management Service, Pharmacist Service) communicate via **gRPC** using these shared Protobuf contracts.

---

## 📂 Project Structure
.
├── genproto/ # Auto-generated Go code from .proto files
│ ├── adminpb/ # Admin Panel gRPC definitions
│ ├── doctorpb/ # Doctor Service gRPC definitions
│ ├── nursepb/ # Nurse Service gRPC definitions
│ ├── patientpb/ # Patient Management gRPC definitions
│ └── pharmacistpb/ # Pharmacist Service gRPC definitions
│
├── protos/ # Source .proto files
│ ├── admin-panel-service/
│ ├── doctor-service/
│ ├── nurse-service/
│ ├── patient-management-service/
│ └── pharmacist-service/
│
├── Makefile # Helper commands for generating code
├── go.mod / go.sum # Go module dependencies
└── README.md # Project documentation