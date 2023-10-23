# go-admin-ui


[![Build Status](https://github.com/nicelizhi/go-admin-api/workflows/build/badge.svg)](https://github.com/nicelizhi/go-admin-api)
[![Release](https://img.shields.io/github/release/nicelizhi/go-admin-api.svg?style=flat-square)](https://github.com/nicelizhi/go-admin-api/releases)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/nicelizhi/go-admin-api)

English | [简体中文](https://github.com/nicelizhi/go-admin-api/blob/master/README.Zh-cn.md)

The front-end and back-end separation authority management system based on Gin + Vue + Element UI is extremely simple to initialize the system. You only need to modify the database connection in the configuration file. The system supports multi-instruction operations. Migration instructions can make it easier to initialize database information. Service instructions It's easy to start the api service.

[Backend project](https://github.com/nicelizhi/go-admin)


## ✨ Feature

- Follow RESTful API design specifications

- Based on the GIN WEB API framework, it provides rich middleware support (user authentication, cross-domain, access log, tracking ID, etc.)

- RBAC access control model based on Casbin

- JWT authentication

- Support Swagger documents (based on swaggo)

- Database storage based on GORM, which can expand multiple types of databases

- Simple model mapping of configuration files to quickly get the desired configuration

- Code generation tool

- Form builder

- Multi-command mode

- TODO: unit test


## 🎁 Internal

1. User management: The user is the system operator, this function mainly completes the system user configuration.
2. Department management: configure the system organization (company, department, group), and display the tree structure to support data permissions.
3. Position management: configure the positions of system users.
4. Menu management: configure the system menu, operation authority, button authority identification, interface authority, etc.
5. Role management: Role menu permission assignment and role setting are divided into data scope permissions by organization.
6. Dictionary management: Maintain some relatively fixed data frequently used in the system.
7. Parameter management: dynamically configure common parameters for the system.
8. Operation log: system normal operation log record and query; system abnormal information log record and query.
9. Login log: The system login log record query contains login exceptions.
1. Interface documentation: Automatically generate related api interface documents according to the business code.
1. Code generation: According to the data table structure, generate the corresponding addition, deletion, modification, and check corresponding business, and the whole process of visual operation, so that the basic business can be implemented with zero code.
1. Form construction: Customize the page style, drag and drop to realize the page layout.
1. Service monitoring: View the basic information of some servers.
1. Content management: demo function, including classification management and content management. You can refer to the easy to use quick start.