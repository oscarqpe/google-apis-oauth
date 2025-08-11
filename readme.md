# Google APIs OAuth

This project contains Python scripts to generate OAuth 2.0 refresh tokens for Google APIs.

## Getting Started

### Prerequisites

- Python 3.7+
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/oscarqpe/google-apis-oauth.git
   cd google-apis-oauth
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Google Ads API

To generate a refresh token for the Google Ads API, run the following command:

```bash
python generate_refresh_token.py --client_secrets_path /path/to/your/client_secrets.json
```

### Display & Video 360 API

To generate a refresh token for the Display & Video 360 API, run the following command:

```bash
python generate_refresh_token_dv360.py --client_secrets_path /path/to/your/client_secrets.json
```

### Additional Scopes

You can also specify additional scopes using the `--additional_scopes` flag:

```bash
python generate_refresh_token.py --client_secrets_path /path/to/your/client_secrets.json --additional_scopes "scope1,scope2"
```

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
