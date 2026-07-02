# Domain-level-cluster-policies
policies/
pod security/
validate/
01-no-disallow-privilleged-containers
02-no-require-run-as-non-root
03-no-disallow-host-namespace
04-no-require-drop-capabilities
rbac/
validate/
01-no-restrict-cluster-admin-binding
02-no-disable-automount-service-account-token
network/
validate/
01-no-generate-default-deny-all
02-n0-restrict-external-ips
image security/
validate/
01-no-restrict-image-registries
02-no-disallow-latest-tag
resources/
validate/
01-no-request-resource-limita
02-no-add-default-resources
storage/
validate/
01-limit-emptydir-size
tests/
pod security/
.github/
workflows/
