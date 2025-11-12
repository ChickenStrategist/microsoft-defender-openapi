# Microsoft Defender for Endpoint API

Official OpenAPI 3.0 specification for Microsoft Defender API integration with Rewst.

## Documentation
[Rewst Custom Integration Guide](https://docs.rewst.help/documentation/configuration/integrations/custom-integrations/custom-integrations-v2)

## Specification Details
- **Version**: 2.0.0
- **Base URL**: `https://api.securitycenter.microsoft.com`
- **Authentication**: oauth2

## Description
Microsoft Defender for Endpoint API provides programmatic access to Microsoft Defender for Endpoint capabilities including machine management, security recommendations, alerts, and threat intelligence. This specification has been rebuilt from comprehensive documentation analysis for 100% accuracy.

## Usage

### Import into Rewst
1. Navigate to: Rewst Dashboard > Configuration > Integrations
2. Create Custom Integration
3. Upload `openapi.json` from this repository
4. Configure authentication parameters
5. Test connection

### Import into API Testing Tools
- **Postman**: Import > Link > Paste raw GitHub URL
- **Insomnia**: Import > URL > Paste raw GitHub URL
- **OpenAPI Generator**: `openapi-generator-cli generate -i openapi.json`

## Repository Structure
```
.
├── openapi.json              # Primary OpenAPI 3.0 specification
├── assets/                   # Integration assets (logos, guides)
├── README.md                 # This file
└── .github/
    └── workflows/
        └── validate-openapi.yml  # CI validation
```

## Validation
This specification is automatically validated on every commit using GitHub Actions.

## Contributing
Maintained by Rewst APAC Automation Team.

## Support
- **Technical Support**: roc@rewst.io
- **Documentation**: [Rewst Docs](https://docs.rewst.help)

## License
Private repository - Rewst LLC internal use only.
