## sample-controller style code

cd /Users/tamal/go/src/kubedb.dev/apimachinery

gen-api-reference-docs --v=3 \
  -config=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/example-config.json \
  -api-dir=./apis \
  -out-dir=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/.dev

gen-api-reference-docs --v=3 \
  -config=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/example-config.json \
  -api-dir=./apis \
  -http-addr=:8081

## Stash docs

cd /Users/tamal/go/src/stash.appscode.dev/apimachinery

gen-api-reference-docs --v=3 \
  -config=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/example-config.json \
  -api-dir=./apis \
  -http-addr=:8081

## Kubeform docs

cd /Users/tamal/go/src/kubeform.dev/provider-aws-api

gen-api-reference-docs --v=3 \
  -config=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/example-config.json \
  -api-dir=./apis \
  -http-addr=:8081


## Doc for Kubebuilder Generated CRDs

cd /Users/tamal/go/src/github.com/tamalsaha/kubebuilder-multi-apigroup

gen-api-reference-docs --v=3 \
  -config=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/example-config.json \
  -api-dir=./apis \
  -out-file=/Users/tamal/go/src/go.crdhub.dev/gen-api-reference-docs/.dev/kb.html
