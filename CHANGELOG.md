# CHANGELOG

Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

### 💥 Breaking Changes

### Deprecations

### 🛡 Security

- [Legacy Maps Plugin] Prevent reverse-tabnabbing ([#2540](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2540))
- Eliminate dependency on `got` versions older than 11.8.5 ([#2801](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2801))
- [Multi DataSource] Add explicit no spellcheck on password fields ([#2818](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2818))

### 📈 Features/Enhancements

- [MD] Support legacy client for data source ([#2204](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2204))
- [MD] Add data source signing support ([#2510](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2510))
- [Plugin Helpers] Facilitate version changes ([#2398](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2398))
- [MD] Display error toast for create index pattern with data source ([#2506](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2506))
- [Multi DataSource] UX enhancement on index pattern management stack ([#2505](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2505))
- [Multi DataSource] UX enhancement on Data source management stack ([#2521](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2521))
- [Multi DataSource] UX enhancement on Index Pattern management stack ([#2527](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2527))
- [Multi DataSource] Add data source column into index pattern table ([#2542](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2542))
- [Multi DataSource] UX enhancement for Data source management creation page ([#2051](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2501))
- [Multi DataSource] Add experimental callout for index pattern section ([#2523](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2523))
- [Multi DataSource] Add data source config to opensearch-dashboards-docker ([#2557](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2557))
- [Multi DataSource] Make text content dynamically translated & update unit tests ([#2570](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2570))
- [Vis Builder] Change classname prefix wiz to vb ([#2581](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2581/files))
- [Vis Builder] Change wizard to vis_builder in file names and paths ([#2587](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2587))
- [Windows] Facilitate building and running OSD and plugins on Windows platforms ([#2601](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2601))
- [Windows] Add `@osd/cross-platform` package to standardize path handling across platforms ([#2703](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2703))
- [Multi DataSource] Address UX comments on Data source list and create page ([#2625](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2625))
- [Vis Builder] Rename wizard to visBuilder in i18n id and formatted message id ([#2635](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2635))
- [Vis Builder] Rename wizard to visBuilder in class name, type name and function name ([#2639](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2639))
- [Vis Builder] Rename wizard on save modal and visualization table ([#2645](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2645))
- [Vis Builder] Adds functional tests to CI ([#2728](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2728))
- [Vis Builder] Enable VisBuilder by default ([#2725](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2725))
- Change save object type, wizard id and name to visBuilder #2673 ([#2673](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2673))
- [Multi DataSource] Update MD data source documentation link ([#2693](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2693))
- [Save Object Aggregation View] Add extension point in saved object management to register namespaces and show filter ([#2656](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2656))
- [Save Object Aggregation View] Fix for export all after scroll count response changed in PR#2656 ([#2696](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2696))
- [Vis Builder] Add an experimental table visualization in vis builder ([#2705](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2705))
- [Vis Builder] Add field summary popovers ([#2682](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2682))

### 🐛 Bug Fixes

- [Vis Builder] Fixes auto bounds for timeseries bar chart visualization ([2401](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2401))
- [Vis Builder] Fixes visualization shift when editing agg ([2401](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2401))
- [Vis Builder] Renames "Histogram" to "Bar" in vis type picker ([2401](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2401))
- [Vis Builder] Update vislib params and misc fixes ([2610](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2610))
- [Vis Builder] Bug fixes for datasource picker and auto time interval ([2632](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2632))
- [MD] Add data source param to low-level search call in Discover ([#2431](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2431))
- [Multi DataSource] Skip data source view in index pattern step when pick default ([#2574](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2574))
- [Multi DataSource] Address UX comments on Edit Data source page ([#2629](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2629))
- [BUG] Fix suggestion list cutoff issue ([#2607](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2607))
- [Multi DataSource] Address UX comments on index pattern management stack ([#2611](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2611))
- [Multi DataSource] Apply get indices error handling in step index pattern ([#2652](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2652))
- [Vis Builder] Last Updated Timestamp for visbuilder savedobject is getting Generated ([#2628](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2628))
- Removed Leftover X Pack references ([#2638](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2638))
- Removes Add Integration button ([#2723](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2723))
- Change geckodriver version to make consistency ([#2772](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2772))
- [Multi DataSource] Update default audit log path ([#2793](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2793))
- [Table Visualization] Fix first column sort issue ([#2828](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2828))
- Temporary workaround for task-kill exceptions on Windows when it is passed a pid for a process that is already dead ([#2842](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2842))
- [Vis Builder] Fix empty workspace animation does not work in firefox ([#2853](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2853))

### 🚞 Infrastructure

- Add CHANGELOG.md and related workflows ([#2414](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2414))
- Update backport custom branch name to utilize head template ([#2766](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2766))

### 📝 Documentation

- Add the release runbook to RELEASING.md ([#2533](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2533))
- [MD] Add design documents of multiple data source feature [#2538](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2538)
- [MD] Tweak multiple data source design doc [#2724](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2724)

### 🛠 Maintenance

- Adding @zhongnansu as maintainer. ([#2590](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2590))

### 🪛 Refactoring

- [MD] Refactor data source error handling ([#2661](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2661))
- Refactor and improve Discover field summaries ([#2391](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2391))
- [Vis Builder] Removed Hard Coded Strings and Used i18n to transalte([#2867](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2867))

### 🔩 Tests

- [Multi DataSource] Add unit test coverage for Update Data source management stack ([#2567](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2567))

## [2.x]

### 💥 Breaking Changes

### Deprecations

### 🛡 Security

- Use a forced CSP-compliant interpreter with Vega visualizations ([#2352](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2352))
- Bump moment-timezone from 0.5.34 to 0.5.37 ([#2361](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2361))
- [CVE-2022-33987] Upgrade geckodriver to 3.0.2 ([#2166](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2166))
- Bumps percy-agent to use non-beta version ([#2415](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2415))
- Resolve sub-dependent d3-color version and potential security issue ([#2454](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2454))
- [CVE-2022-3517] Bumps minimatch from 3.0.4 to 3.0.5 and [IBM X-Force ID: 220063] unset-value from 1.0.1 to 2.0.1 ([#2640](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2640))
- [CVE-2022-37601] Bump loader-utils to 2.0.3 ([#2689](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2689))

### 📈 Features/Enhancements

- Add updated_at column to objects' tables ([#1218](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/1218))
- [Viz Builder] State validation before dispatching and loading ([#2351](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2351))
- [Viz Builder] Create a new wizard directly on a dashboard ([#2384](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2384))
- [Viz Builder] Edit wizard directly on dashboard ([#2508](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2508))
- [Multi DataSource] UX enhacement on index pattern management stack ([#2505](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2505))
- [Multi DataSource] UX enhancement on Data source management stack ([#2521](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2521))
- [Multi DataSource] UX enhancement on Update stored password modal for Data source management stack ([#2532](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2532))

### 🐛 Bug Fixes

- [Viz Builder] Fixes time series for new chart types ([#2309](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2309))
- [Viz Builder] Add index pattern info when loading embeddable ([#2363](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2363))
- Fixes management app breadcrumb error ([#2344](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2344))
- [BUG] Fix suggestion list cutoff issue ([#2607](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2607))

### 🚞 Infrastructure

- Add path ignore for markdown files for CI ([#2312](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2312))
- Updating WS scans to ignore BWC artifacts in `cypress` ([#2408](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2408))
- [CI] Run functional test repo as workflow ([#2503](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2503))

### 📝 Documentation

- README.md for saving index pattern relationship ([#2276](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2276))
- Remove extra typo from README. ([#2403](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2403))
- Add sample config for multi data source feature in yml template. ([#2428](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2428))
- README.md for dataSource and dataSourceManagement Plugin ([#2448](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2448))
- Updates functionl testing information in Testing.md ([#2492](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2492))

### 🛠 Maintenance

- Increment from 2.3 to 2.4. ([#2295](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2295))
- Adding @zengyan-amazon as maintainer ([#2419](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2419))
- Updating @tmarkley to Emeritus status. ([#2423](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2423))
- Adding sample config for multi data source in yml config template. ([#2428](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2428))
- Adding @kristenTian as maintainer. ([#2450](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2450))

### 🪛 Refactoring

### 🔩 Tests

- Update caniuse to fix failed integration tests ([#2322](https://github.com/opensearch-project/OpenSearch-Dashboards/pull/2322))

[unreleased]: https://github.com/opensearch-project/OpenSearch-Dashboards/compare/2.3.0...HEAD
[2.x]: https://github.com/opensearch-project/OpenSearch-Dashboards/compare/2.3.0...2.x
