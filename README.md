# Harness CD & GitOps Example Apps test6

This repository contains example applications for demoing Harness CD & GitOps functionality. Feel free
use this to learn more about Harness CD & GitOps in your own Harness account, or fork this repo and push your own commits!

| Application | Description |
|-------------|-------------|
| [guestbook](guestbook/) | A hello word guestbook app as plain YAML |
| [ksonnet-guestbook](ksonnet-guestbook/) | The guestbook app as a ksonnet app |
| [helm-guestbook](helm-guestbook/) | The guestbook app as a Helm chart |
| [jsonnet-guestbook](jsonnet-guestbook/) | The guestbook app as a raw jsonnet |
| [jsonnet-guestbook-tla](jsonnet-guestbook-tla/) | The guestbook app as a raw jsonnet with support for top level arguments |
| [kustomize-guestbook](kustomize-guestbook/) | The guestbook app as a Kustomize 2 app |
| [pre-post-sync](pre-post-sync/) | Demonstrates Harness CD PreSync and PostSync hooks |
| [sync-waves](sync-waves/) | Demonstrates Harness CD sync waves with hooks |
| [helm-dependency](helm-dependency/) | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo |
| [sock-shop](sock-shop/) | A microservices demo app (https://microservices-demo.github.io) |
| [plugins](plugins/) | Apps which demonstrate config management plugins usage |
| [blue-green](blue-green/) | Demonstrates how to implement blue-green deployment using Harness CD|
| [apps](apps/) | An app composed of other apps |

## Auto-Merge Test
Testing the automated PR merge workflow with GitHub Actions and Harness integration.

Webhook test - Mon Apr  6 13:12:20 IST 2026

Webhook test - trigger after webhook configured - Mon Apr  6 13:41:13 IST 2026

Final webhook test with dynamic PR number - Mon Apr  6 13:51:16 IST 2026

Final webhook test with new trigger - Mon Apr  6 14:17:07 IST 2026
