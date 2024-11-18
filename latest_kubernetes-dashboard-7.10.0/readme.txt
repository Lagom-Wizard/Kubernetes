web/v1.6.0
Image
docker.io/kubernetesui/dashboard-web:1.6.0
Assets 2
Source code
(zip)
2 weeks ago
Source code
(tar.gz)
2 weeks ago
kubernetes-dashboard-7.10.0
2 weeks ago
@github-actions github-actions
 kubernetes-dashboard-7.10.0
 41611ad
kubernetes-dashboard-7.10.0 Latest
What's Changed
fix(api): ssar resource kind name and resource updates by @floreks in #9599
fix(signin button): signin button is clickable when token is autofilled by browser by @lsq645599166 in #9610
feat: allow hiding "All namespaces" in namespaces dropdown list by @avanish23 in #9547
chore(chart): release 7.10.0 by @floreks in #9621
Dependency updates
chore(deps-dev): bump @babel/core from 7.25.8 to 7.25.9 in /modules/web by @dependabot in #9565
chore(deps-dev): bump @types/node from 22.7.8 to 22.7.9 in /modules/web by @dependabot in #9569
chore(deps): bump http-proxy-middleware from 2.0.6 to 2.0.7 in /modules/web by @dependabot in #9574
chore(deps-dev): bump @graphql-mesh/transform-replace-field from 0.102.7 to 0.102.9 in /modules/web by @dependabot in #9578
chore(deps-dev): bump @graphql-mesh/openapi from 0.107.1 to 0.107.3 in /modules/web by @dependabot in #9575
chore(deps-dev): bump @babel/preset-env from 7.25.8 to 7.25.9 in /modules/web by @dependabot in #9564
chore(deps-dev): bump @types/jest from 29.5.13 to 29.5.14 in /modules/web by @dependabot in #9571
chore(deps-dev): bump @graphql-mesh/runtime from 0.103.8 to 0.103.10 in /modules/web by @dependabot in #9577
chore(deps-dev): bump @babel/register from 7.25.7 to 7.25.9 in /modules/web by @dependabot in #9570
chore(deps-dev): bump sass from 1.80.3 to 1.80.4 in /modules/web by @dependabot in #9587
chore(deps): bump actions/setup-go from 5.0.2 to 5.1.0 by @dependabot in #9592
chore(deps-dev): bump cypress from 13.15.0 to 13.15.1 in /modules/web by @dependabot in #9597
chore(deps-dev): bump @graphql-mesh/runtime from 0.103.10 to 0.103.11 in /modules/web by @dependabot in #9596
chore(deps-dev): bump @graphql-mesh/transform-replace-field from 0.102.9 to 0.102.10 in /modules/web by @dependabot in #9595
chore(deps-dev): bump @graphql-mesh/openapi from 0.107.3 to 0.107.4 in /modules/web by @dependabot in #9593
chore(deps-dev): bump sass from 1.80.4 to 1.80.5 in /modules/web by @dependabot in #9614
chore(deps-dev): bump @typescript-eslint/eslint-plugin from 8.11.0 to 8.12.2 in /modules/web by @dependabot in #9613
chore(deps-dev): bump @babel/preset-env from 7.25.9 to 7.26.0 in /modules/web by @dependabot in #9604
chore(deps-dev): bump @typescript-eslint/parser from 8.11.0 to 8.12.2 in /modules/web by @dependabot in #9612
chore(deps-dev): bump @babel/core from 7.25.9 to 7.26.0 in /modules/web by @dependabot in #9603
chore(deps-dev): bump @types/node from 22.7.9 to 22.8.4 in /modules/web by @dependabot in #9611
New Contributors
@lsq645599166 made their first contribution in #9610
@avanish23 made their first contribution in #9547
Full Changelog: kubernetes-dashboard-7.9.0...kubernetes-dashboard-7.10.0

Installation
helm repo add kubernetes-dashboard https://kubernetes.github.io/dashboard/
helm upgrade --install kubernetes-dashboard kubernetes-dashboard/kubernetes-dashboard --create-namespace --namespace kubernetes-dashboard
Compatibility
Kubernetes version	1.28	1.29	1.30	1.31
Compatibility	?	?	?	✓
✓ Fully supported version range.
? Due to breaking changes between Kubernetes API versions, some features might not work correctly in the Dashboard.
Images
docker.io/kubernetesui/dashboard-api:1.10.1
docker.io/kubernetesui/dashboard-auth:1.2.2
docker.io/kubernetesui/dashboard-metrics-scraper:1.2.1
docker.io/kubernetesui/dashboard-web:1.6.0
Contributors
@floreks
@lsq645599166
@dependabot
@avanish23
floreks, lsq645599166, and 2 other contributors
Assets 3
kubernetes-dashboard-7.10.0.tgz
363 KB
2 weeks ago
Source code
(zip)
2 weeks ago
Source code
(tar.gz)
2 weeks ago
1 person reacted
web/v1.5.2
3 weeks ago
@github-actions github-actions
 web/v1.5.2
 8c15a76
web/v1.5.2
Image
docker.io/kubernetesui/dashboard-web:1.5.2
Assets 2
Source code
(zip)
3 weeks ago
Source code
(tar.gz)
3 weeks ago
auth/v1.2.2
3 weeks ago
@github-actions github-actions
 auth/v1.2.2
 8c15a76
auth/v1.2.2
Image
docker.io/kubernetesui/dashboard-auth:1.2.2
Assets 2
Source code
(zip)
3 weeks ago
Source code
(tar.gz)
3 weeks ago
api/v1.10.1
3 weeks ago
@github-actions github-actions
 api/v1.10.1
 8c15a76
api/v1.10.1
Image
docker.io/kubernetesui/dashboard-api:1.10.1
Assets 2
Source code
(zip)
3 weeks ago
Source code
(tar.gz)
3 weeks ago
1 person reacted
web/v1.5.1
last month
@maciaszczykm maciaszczykm
 web/v1.5.1
 9d28815
web/v1.5.1
Image
docker.io/kubernetesui/dashboard-web:1.5.1
Assets 2
Source code
(zip)
last month
Source code
(tar.gz)
last month
metrics-scraper/v1.2.1
last month
@maciaszczykm maciaszczykm
 metrics-scraper/v1.2.1
 9d28815
metrics-scraper/v1.2.1
Image
docker.io/kubernetesui/dashboard-metrics-scraper:1.2.1
Assets 2
Source code
(zip)
last month
Source code
(tar.gz)
last month