# CodSoft Task 3: Nginx Web Server Deployment

## Objective
Deploy static websites using Nginx and configure virtual hosts
and custom 404 error pages.

## Technologies
- Nginx
- Docker
- HTML
- Git and GitHub

## Websites
- Website 1: site1.local
- Website 2: site2.local

## Local Access
- Nginx server: http://localhost:8081
- Website 1: tested using the Host header site1.local
- Website 2: tested using the Host header site2.local

## Features
- Nginx web server running in a Linux-based container
- Two virtual hosts
- Custom 404 error pages
- HTTP response testing
- Basic response-time test

## Build and Run
```bash
docker build -t codsoft-nginx-task3 .
docker run -d --name codsoft-nginx -p 8081:80 codsoft-nginx-task3
```

## Verification
Test both virtual hosts, request a missing page to verify
the custom 404 responses, and record the performance test result.