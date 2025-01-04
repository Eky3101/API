Project Structure



├── postman/
│   ├── Weather.json  # Postman Collection JSON File
├── reports/
│   ├── result.json  # Newman Report (in JSON format)
│   └── result.html  # Human-readable report
└── README.md  # Project setup and instructions


Steps to RUN:
- Download all files in this repository
- Open with Postman.
- You can also create a report with this code
  newman run Weather.json --reporters cli,html,json --reporter-json-export outputfile.json --reporter-html-export "reports/report1.html"


