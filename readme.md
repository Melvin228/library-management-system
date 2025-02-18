# Library Management System

## 📥 Cloning the Repository with Submodules

This project uses **Git Submodules** to manage individual microservices separately. To properly clone the repository with all submodules, follow these steps:

### **🔹 Clone with Submodules**
```sh
git clone --recursive https://github.com/your-username/library-management-system.git
```

### **🔹 Update Submodules After Cloning**
```sh
git submodule update --init --recursive
```

### **🔹 🔄 Pull Latest Changes from Main Repo & Submodules**
```sh
git pull --recurse-submodules
git submodule update --remote --merge
```

### **🔹 🔄 Add a New Submodule**
```sh
git submodule add https://github.com/your-username/user-service.git backend/user-service
```