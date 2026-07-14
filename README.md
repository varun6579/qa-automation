workflowpro-qa-automation-assessment/
│
├── README.md
├── requirements.txt
├── pytest.ini
├── .env.example
├── browserstack.yml
├── playwright.config.py
│
├── config/
│   ├── config.py
│   ├── qa.json
│   ├── staging.json
│   └── production.json
│
├── pages/
│   ├── base_page.py
│   ├── login_page.py
│   ├── dashboard_page.py
│   └── project_page.py
│
├── api/
│   ├── api_client.py
│   ├── auth_api.py
│   └── project_api.py
│
├── fixtures/
│   ├── browser_fixture.py
│   ├── api_fixture.py
│   └── tenant_fixture.py
│
├── utils/
│   ├── logger.py
│   ├── helpers.py
│   ├── retry.py
│   └── screenshot.py
│
├── testdata/
│   ├── users.json
│   └── projects.json
│
├── tests/
│   ├── ui/
│   │   ├── test_login.py
│   │   └── test_dashboard.py
│   │
│   ├── api/
│   │   └── test_projects.py
│   │
│   └── integration/
│       └── test_project_creation_flow.py
│
├── reports/
│
└── docs/
    └── QA_Automation_Assessment.md
