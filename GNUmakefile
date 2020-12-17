generate-changelog:
	@echo "==> Generating changelog..."
	@sh -c "'$(CURDIR)/scripts/generate-changelog.sh'"

tools:
	cd tools && GO111MODULE=on go install github.com/hashicorp/go-changelog/cmd/changelog-build

.PHONY: generate-changelog tools
