vault_manager/
├── config/
│   └── default_config.json         # Default predefined folder structure
│
├── vault/                          # Created at runtime, the actual "vault"
│   └── (generated folders/files)
│
├── src/
│   ├── __init__.py
│   ├── main.py                     # Entry point
│   ├── vault.py                    # Vault creation logic
│   ├── file_utils.py               # File/folder operations
│   └── config_handler.py           # Load/save config
│
├── tests/
│   └── test_vault.py               # Optional unit tests
│
├── .gitignore
├── requirements.txt                # Optional dependencies
└── README.md