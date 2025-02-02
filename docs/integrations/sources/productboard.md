# Productboard
A manifest only source for Productboard. https://www.productboard.com/

## Configuration

| Input | Type | Description | Default Value |
|-------|------|-------------|---------------|
| `access_token` | `string` | Access Token. Your Productboard access token. See https://developer.productboard.com/reference/authentication for steps to generate one. |  |
| `start_date` | `string` | Start date.  |  |

## Streams
| Stream Name | Primary Key | Pagination | Supports Full Sync | Supports Incremental |
|-------------|-------------|------------|---------------------|----------------------|
| products | id | DefaultPaginator | ✅ |  ❌  |
| features | id | DefaultPaginator | ✅ |  ❌  |
| components | id | DefaultPaginator | ✅ |  ❌  |
| feature-statuses | id | DefaultPaginator | ✅ |  ❌  |
| notes | id | DefaultPaginator | ✅ |  ✅  |
| tags |  | No pagination | ✅ |  ❌  |
| links |  | No pagination | ✅ |  ❌  |
| feedback-form-configurations | id | DefaultPaginator | ✅ |  ❌  |
| companies | id | DefaultPaginator | ✅ |  ❌  |
| company-custom-fields |  | DefaultPaginator | ✅ |  ❌  |
| users | id | DefaultPaginator | ✅ |  ❌  |
| custom-fields |  | DefaultPaginator | ✅ |  ❌  |
| custom-fields-values |  | DefaultPaginator | ✅ |  ❌  |
| release-groups | id | DefaultPaginator | ✅ |  ❌  |
| releases | id | DefaultPaginator | ✅ |  ❌  |
| feature-release-assignments |  | DefaultPaginator | ✅ |  ❌  |
| objectives | id | DefaultPaginator | ✅ |  ❌  |

## Changelog

<details>
  <summary>Expand to review</summary>

| Version | Date       | Pull Request                                             | Subject                                                                                   |
|---------|------------|----------------------------------------------------------|-------------------------------------------------------------------------------------------|
| 0.0.5 | 2024-11-05 | [48365](https://github.com/airbytehq/airbyte/pull/48365) | Revert to source-declarative-manifest v5.17.0 |
| 0.0.4 | 2024-11-05 | [48324](https://github.com/airbytehq/airbyte/pull/48324) | Update dependencies |
| 0.0.3 | 2024-10-29 | [47774](https://github.com/airbytehq/airbyte/pull/47774) | Update dependencies |
| 0.0.2 | 2024-10-28 | [47677](https://github.com/airbytehq/airbyte/pull/47677) | Update dependencies |
| 0.0.1 | 2024-09-13 | [45449](https://github.com/airbytehq/airbyte/pull/45449) | Initial release by [@pabloescoder](https://github.com/pabloescoder) via Connector Builder |

</details>
