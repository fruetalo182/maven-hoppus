

<div align="left">

![Hoppus](src/main/resources/mark.png)

<h1>Maven Hoppus</h1>

  [![CI Status](https://img.shields.io/github/actions/workflow/status/fruetalo182/maven-hoppus/ci.yaml?branch=main&label=CI%20Status)](https://github.com/fruetalo182/maven-hoppus/actions/workflows/ci.yaml)
  
  ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring&logoColor=white)
  ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
  ![REST API](https://img.shields.io/badge/REST%20API-00BFFF?style=flat&logo=api&logoColor=white)
  ![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat&logo=junit&logoColor=white)

</div>

```Maven Hoppus``` is one of the three members deployed on ```cluster182```

## 📋 Requirements

- **Java version:** 11 or higher
- **Maven version:** 3.6 or higher


## ⚙️ Local setup

1. Clone this repository:
    ```bash
    git clone https://github.com/fruetalo182/maven-hoppus.git
    cd maven-hoppus
    ```
2. Build the application:
    ```bash
    mvn clean package
    ```
3. Run the application:
    ```bash
    mvn spring-boot:run
    ```
4. Open your browser at [http://localhost:8080](http://localhost:8080) to access.


## 🐳 Docker setup

To run the Maven Hoppus application using Docker, follow these steps:

1. **Pull the Docker image**:

    ```bash
    docker pull ghcr.io/fruetalo182/maven-hoppus:latest
    ```

2. **Run the Docker container**:

    ```bash
    docker run -p 8080:8080 maven-hoppus
    ```

3. **Access the application** at [http://localhost:8080](http://localhost:8080).


