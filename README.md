# Demo of ACME Fitness App

## Getting Started

These instructions will allow you to run entire ACME Fitness App 

## Requirements

Based on the type of deployment the requirements will vary 

1. **docker-compose** - Needs docker-compose version 1.23.1+
2. **kubernetes**

Other deployment modes coming soon

## Instructions

1. Clone this repository 

2. You will notice the following directory structure

``` 
.
├── README.md
├── docker-compose
│   ├── README.md
│   └── docker-compose.yml
└── kubernetes-manifests
    ├── README.md
    ├── cart-redis-total.yaml
    ├── cart-total.yaml
    ├── catalog-db-initdb-configmap.yaml
    ├── catalog-db-total.yaml
    ├── catalog-total.yaml
    ├── frontend-total.yaml
    ├── order-db-total.yaml
    ├── order-total.yaml
    ├── payment-total.yaml
    ├── users-db-initdb-configmap.yaml
    ├── users-db-total.yaml
    └── users-total.yaml
```

3. Switch to the appropriate directory for deployment

a. [docker-compose](docker-compose/README.md)  
b. [kubernetes-manifest](kubernetes-manifests/README.md)  


### Additional Info