# Gearbox platform
University project from OOA&amp;P subject

### Main goal of this project is to develop an SPA that will allow users to manage all their cloud storages in one place

* 10 GB Space in our platform
* Up to 3 accounts of Google Drive, OneDrive, DropBox, IDrive
* Search, download and view files
* Transfers between different services with one click
* Share your files with another users

### Service architecture and tech stack

* django backend
* React frontend
* graphql

* AWS EC2
* AWS S3
* AWS RDS

### Patterns usage

* Thread pool concurrency pattern for mass file transfers and files download
* Strategy pattern for API requests implementation
* Template Method pattern for file transfers