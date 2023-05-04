.PHONY: generate
generate:
	helmfile --version
	helmfile repos
	helmfile template --include-crds > generated.yaml