# Form Sample

## Description
This project runs a Spring Boot based application server server with a simple form that collects user information (Name,
Age, Title, Hometown). When submitted, it displays the submitted entry along with a table of all previous submissions.

## Features
- Server-side validation (Name and Title are required)
- Confirmation screen with all past submissions
- Clean, responsive styling using basic CSS
- Built using Java, Spring Boot, and Thymeleaf

## Installation
To build the project, clone the repository and run the following from the root directory:
### Linux or Mac
```console
./mvnw clean install
```
### Windows
```console
.\mvnw.cmd clean install
```
## Usage
### Option 1: Running from the JAR file
```console
java -jar target/form-sample-0.0.1-SNAPSHOT.jar
```
### Option 2: Run directly with Maven wrapper
#### Linux or Mac
```console
./mvnw spring-boot:run
```
#### Windows
```console
.\mvnw.cmd spring-boot:run
```
Once running, visit: http://localhost:8080/form
## Support
If there are any problems with this project, please email treeden53@gmail.com.

## Authors and acknowledgment
Walden Hart - Author

## License
MIT License

Copyright (c) 2025 Walden Hart

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.****