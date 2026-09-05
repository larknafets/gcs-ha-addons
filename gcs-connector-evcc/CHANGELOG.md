Full release details: https://github.com/larknafets/gcs-connector-evcc/releases

## [v0.0.8] - 2026-09-05

## Changelog
* Store HA add-on state.json under addon_config, not /data



## [v0.0.7] - 2026-08-26

## Changelog
* Add CI workflow: go test and golangci-lint on push/PR
* Add Dependabot config for gomod, github-actions, and docker
* Bump docker/build-push-action from 6.19.2 to 7.3.0 (#35)
* Bump docker/login-action from 3.7.0 to 4.6.0 (#36)
* Bump docker/setup-buildx-action from 3.12.0 to 4.3.0 (#37)
* Bump docker/setup-qemu-action from 3.7.0 to 4.2.0 (#33)
* Bump github.com/stretchr/testify in the go-dependencies group (#32)
* Bump goreleaser/goreleaser-action from 6.4.0 to 7.2.3 (#34)
* Fix CI: pin golangci-lint-action to v9.3.0, lint version to v2.13.0
* Fix golangci-lint findings ahead of adding lint CI
* Log public_id and 422 error body from Connector API responses



## [v0.0.6] - 2026-08-20

## Changelog
* Add explicit non-root USER directive to Dockerfile
* Bump golang.org/x/sys to fix integer overflow in NewNTUnicodeString
* Bump golang.org/x/text to fix DoS via invalid UTF-8 input
* Pin third-party GitHub Actions to commit SHAs
* Remove site_name config field
* gofmt: realign struct literal after site_name removal



## [v0.0.5] - 2026-08-18

## Changelog
* Deepen Config validation: merge FromMap/FromOptionsJSON's duplicated rules
* Give the session-eligibility pipeline a real interface, not an implied call order
* Put a seam under Orchestrator's evcc/GCS dependencies
* Record ADR-0001: wizard.RunInit stays thin and untested
* Stop gcs.Client's logger leaking across the package seam



## [v0.0.4] - 2026-08-17

## Changelog
* Fix hassio job: git commit -am silently drops new files (#24)



## [v0.0.3] - 2026-08-17

## Changelog
* Mirror release notes into gcs-hassio-addons's CHANGELOG.md (#22)
* Mirror release version into gcs-hassio-addons on tag push (#20)
* Rename clean_percentage to green_percentage (#21)
* Update add-on repo references: gcs-hassio-addons -> gcs-ha-addons (#23)



## [v0.0.2] - 2026-08-16

## Changelog
* Document the Home Assistant add-on as an installation option
* Support Home Assistant Supervisor options.json as a config source (#19)



## [v0.0.1] - 2026-08-16

## Changelog
* Add Docker Compose installation variant to README
* Add README with feature overview and installation instructions
* Add agent-skills config: issue tracker and domain-docs conventions
* Default sync_interval_minutes to 60, add optional sync-now webhook
* Fix Go version mismatch between go.mod and Docker/CI build images
* Fix vehicle_name omission and restore README dev section
* Harden webhook/sync-interval extensions per code-review (#14-#18)
* Implement Kern-Walking-Skeleton spec: evcc-to-GCS sync connector
* Rename repo/module to gcs-connector-evcc
* Update gc-platform references to gcs-platform



