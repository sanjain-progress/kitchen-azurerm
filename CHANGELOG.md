# knife-azurerm Changelog

## [0.2.0] - 2015-09-29
- Added WinRM support, enables WinRM and WinRM/s and configures server for Basic/Negotiate authentication (@stuartpreston) 
- Store server_id earlier so it can be retrieved if resources fail to create in Azure (@stuartpreston)

## [0.1.3] - 2015-09-23
- Support *nix by changing the driver name to lowercase 'azurerm', remove Chef references (@gadgetmg)

## [0.1.2] - 2015-09-23
- Initial release, supports provision of all public image types in Azure (@stuartpreston)