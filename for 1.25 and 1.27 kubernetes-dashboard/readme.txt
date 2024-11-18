auth/v1.1.0
Image
docker.io/kubernetesui/dashboard-auth:1.1.0
Assets 2
api/v1.2.0
Mar 6
@github-actions github-actions
 api/v1.2.0
 3406310
api/v1.2.0
Image
docker.io/kubernetesui/dashboard-api:1.2.0
Assets 2
web/v1.1.1
Mar 4
@maciaszczykm maciaszczykm
 web/v1.1.1
 a75c384
web/v1.1.1
Image
docker.io/kubernetesui/dashboard-web:1.1.1
Assets 2
2 people reacted
metrics-scraper/v1.1.0
Mar 4
@maciaszczykm maciaszczykm
 metrics-scraper/v1.1.0
 94dd3cb
metrics-scraper/v1.1.0
Image
docker.io/kubernetesui/dashboard-metrics-scraper:1.1.0
Assets 2
auth/v1.0.0
Mar 4
@maciaszczykm maciaszczykm
 auth/v1.0.0
 94dd3cb
auth/v1.0.0
Image
docker.io/kubernetesui/dashboard-auth:1.0.0
Assets 2
Source code
(zip)
Mar 4
Source code
(tar.gz)
Mar 4
1 person reacted
api/v1.1.0
Mar 4
@maciaszczykm maciaszczykm
 api/v1.1.0
 94dd3cb
api/v1.1.0
Image
docker.io/kubernetesui/dashboard-api:1.1.0
Assets 2
Source code
(zip)
Mar 4
Source code
(tar.gz)
Mar 4
v3.0.0-alpha0
Jul 7, 2023
@floreks floreks
 v3.0.0-alpha0
 c07a728
v3.0.0-alpha0 Pre-release
Breaking Change
Starting from the release v3 of the Kubernetes Dashboard, the underlying architecture has changed, and it requires a clean installation. Please remove the previous installation first.

Kubernetes Dashboard now uses cert-manager and nginx-ingress-controller by default to work properly. Please make sure you have them installed in your cluster if you want to use a manifest-based installation path. The helm-based approach can install all required dependencies automatically for you if needed.

Compatibility
Kubernetes version	1.25	1.26	1.27
Compatibility	?	?	✓
✓ Fully supported version range.
? Due to breaking changes between Kubernetes API versions, some features might not work correctly in the Dashboard.
Installation
You can now use Helm or a single Manifest to install Kubernetes Dashboard.

Helm
You can install Dashboard using Helm as described here.

Manifest
To install Kubernetes Dashboard using simple manifest and kubectl simply run:

kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v3.0.0-alpha0/charts/kubernetes-dashboard.yaml
Images
Kubernetes Dashboard
WEB
docker.io/kubernetesui/dashboard-web:v1.0.0
API
docker.io/kubernetesui/dashboard-api:v1.0.0
Metrics Scraper
docker.io/kubernetesui/metrics-scraper:v1.0.9
What's Changed
Updated Simplified Chinese translation by @hwdef in #7416
Split frontend and backend by @maciaszczykm in #7047
Use batch/v1 for fetching cronjob jobs by @neoaggelos in #7465
GitHub Workflows security hardening by @sashashura in #7466
Helm update v2.7.0 by @sobi3ch in #7469
fix: update Secret with non-latin1 UTF-8 string by @Senorsen in #7477
Build updates by @floreks in #7478
Update config and dependencies by @maciaszczykm in #7476
Get rid of ng-in-viewport dependency by @floreks in #7479
check the existence of the http member of a ingress rule before iterating through it by @shankerwangmiao in #7481
Bump helm/kind-action from 1.3.0 to 1.4.0 by @dependabot in #7482
Bump helm/chart-testing-action from 2.2.1 to 2.3.1 by @dependabot in #7484
Container resources by @marcosdiez in #7488
Move about page to footer by @maciaszczykm in #7490
Add support for multiarch docker build and deploy by @floreks in #7491
fix:change toleration from master to control-plane by @yosshi825 in #7506
Bump k8s.io/api from 0.25.2 to 0.25.3 in /modules/api by @dependabot in #7501
Bump actions/setup-python from 3.1.2 to 4.3.0 by @dependabot in #7498
Bump k8s.io/client-go from 0.25.2 to 0.25.3 in /modules/api by @dependabot in #7499
yaml link updated by @krouser in #7524
Bump actions/dependency-review-action from 2 to 3 by @dependabot in #7529
Helm Chart: update podDisruptionBudget apiVersion to policy/v1. by @desaintmartin in #7530
Helm Chart: if no image.tag is set, use default appVersion of Chart.yaml by @desaintmartin in #7531
Fix license check by @maciaszczykm in #7518
Bump k8s.io/client-go from 0.25.3 to 0.25.4 in /modules/api by @dependabot in #7528
Bump github.com/emicklei/go-restful/v3 from 3.9.0 to 3.10.0 in /modules/api by @dependabot in #7525
Bump github.com/prometheus/client_golang from 1.13.0 to 1.14.0 in /modules/api by @dependabot in #7520
Replace deprecated k8s registry references. by @jmhbnz in #7513
feat: update Spanish localization by @anyulled in #7492
Bump k8s.io/apiextensions-apiserver from 0.25.2 to 0.25.4 in /modules/api by @dependabot in #7526
Cleanup & build system updates by @floreks in #7537
feat: update Korean localization by @jc01rho in #7514
Bump github.com/emicklei/go-restful/v3 from 3.10.0 to 3.10.1 in /modules/api by @dependabot in #7540
Bump wiremind/helm-kubeval-action from 1.2.1 to 1.2.2 by @dependabot in #7538
Bump golang.org/x/net from 0.1.0 to 0.2.0 in /modules/api by @dependabot in #7539
Fix graphs when using translations by @maciaszczykm in #7546
Fix run command on Mac by @maciaszczykm in #7545
Hide node port 0 and update Go dependencies by @maciaszczykm in #7543
Fix HTTP headers display, restore Go static check and fix typo by @maciaszczykm in #7549
ingress paths are now clickable by @marcosdiez in #7487
Bump golang.org/x/net from 0.2.0 to 0.4.0 in /modules/api by @dependabot in #7555
Bump actions/setup-python from 4.3.0 to 4.3.1 by @dependabot in #7556
Bump k8s.io/api from 0.25.4 to 0.25.5 in /modules/api by @dependabot in #7557
Bump helm/kind-action from 1.4.0 to 1.5.0 by @dependabot in #7562
Bump actions/setup-python from 4.3.1 to 4.4.0 by @dependabot in #7566
Setup development container for new architecture by @shu-mutou in #7563
Update Japanese translation by @shu-mutou in #7570
Bump golang.org/x/net from 0.4.0 to 0.5.0 in /modules/api by @dependabot in #7573
Enable npm update check with dependabot by @shu-mutou in #7574
Add go.mod update check for tools and web by @shu-mutou in #7575
Bump golang.org/x/text from 0.4.0 to 0.6.0 in /modules/web by @dependabot in #7578
Added helm chart optional containers by @daiyyr in #7554
Fix Scale Resource UI by @marcosdiez in #7584
Bump actions/setup-python from 4.4.0 to 4.5.0 by @dependabot in #7588
Bump github.com/cosmtrek/air from 1.40.4 to 1.41.0 in /modules/common/tools by @dependabot in #7590
Bump k8s modules to 0.26.1 by @shu-mutou in #7568
Bump github.com/golangci/golangci-lint from 1.50.1 to 1.51.0 in /modules/common/tools by @dependabot in #7609
Bump github.com/golangci/golangci-lint from 1.51.0 to 1.51.1 in /modules/common/tools by @dependabot in #7610
Bump golang.org/x/text from 0.6.0 to 0.7.0 in /modules/web by @dependabot in #7615
Bump golang.org/x/net from 0.5.0 to 0.6.0 in /modules/api by @dependabot in #7614
Helm: Update CI, upgrade metrics-server by @desaintmartin in #7600
Support kind in development container by @shu-mutou in #7602
Update OWNERS_ALIASES by @shu-mutou in #7620
Update web dependencies by @maciaszczykm in #7619
Fix build in development container by @shu-mutou in #7621
Update Japanese translation guide by @shu-mutou in #7628
Fix port number for dashboard by @shu-mutou in #7629
Document helm chart PodSecurityPolicy deprecation and PodSecurityAdmission alternative by @jmhbnz in #7626
Disable e2e job by @floreks in #7661
Bump github.com/golang/glog from 1.0.0 to 1.1.0 in /modules/web by @dependabot in #7648
Bump golang.org/x/text from 0.7.0 to 0.8.0 in /modules/web by @dependabot in https://github.com/kubernete...
Read more
Contributors
@desaintmartin
@sobi3ch
@anyulled
@marcosdiez
@jeffmaury
@neoaggelos
@floreks
@ViliusS
@maciaszczykm
@jcpunk
@FrenchBen
@Senorsen
@jc01rho
@daiyyr
@mdbudnick
@shankerwangmiao
@testwill
@rjsadow
@shu-mutou
@hwdef
@ColdFire87
@maxime1907
@krouser
@dependabot
@jmhbnz
@laurence-hudson-mindfoundry
@yosshi825
@Thearas
@frozenprocess
@windsonsea
@Kallepan
@sashashura
desaintmartin, sobi3ch, and 30 other contributors
Assets 2
17 people reacted
v2.7.0
Sep 16, 2022
@maciaszczykm maciaszczykm
 v2.7.0
 42deb6b
v2.7.0
What's Changed
Support custom rules for read-only mode by @korjek in #7152
Fix golang 1.19.0 update by @shu-mutou in #7379
feat: added additional rules option to role by @elizaitsev in #7370
Update German translation. by @headcr4sh in #7231
Add ziyi-xie to Japanese i18n reviewers by @shu-mutou in #7413
Update Japanese translation by @shu-mutou in #7415
Fix tags in German translation by @shu-mutou in #7414
Update Korean translation (lines 1001-1500) by @rollony in #7427
Update Korean Translation (lines 1-501) by @bconfiden2 in #7429
Update Korean translation (lines 1501-2000) (#7427) by @Seo-yul in #7428
Update Korean translation (lines 3501-4000) (#7427) by @onestone9900 in #7433
Update Korean translation (lines 4001-4500) by @rollony in #7432
Update Korean translation (lines 4501-5000) by @bconfiden2 in #7434
Update Korean translation (lines 3001-3500) by @BrendenHJH in #7436
Update Korean localization dashboard(5001-5500) by @NayeonKeum in #7440
Update Korean localization dashboard(2001-2500) by @gy-ulbak96 in #7437
Update Korean translation (lines 2501-3000) by @jinnypark9393 in #7435
Update Korean translation (lines 501-1000) by @dewble in #7443
Korean localization for dashboard(5501-6000) by @yuzin9712 in #7446
Korean localization for dashboard(6000-6662) by @having-dlrow in #7447
Bump k8s modules to 0.25.0 and prepare for 2.7.0 release by @shu-mutou in #7316
New Contributors
@korjek made their first contribution in #7152
@elizaitsev made their first contribution in #7370
@rollony made their first contribution in #7427
@bconfiden2 made their first contribution in #7429
@Seo-yul made their first contribution in #7428
@onestone9900 made their first contribution in #7433
@BrendenHJH made their first contribution in #7436
@NayeonKeum made their first contribution in #7440
@gy-ulbak96 made their first contribution in #7437
@jinnypark9393 made their first contribution in #7435
@dewble made their first contribution in #7443
@yuzin9712 made their first contribution in #7446
@having-dlrow made their first contribution in #7447
Full Changelog: v2.6.1...v2.7.0

Compatibility
Kubernetes version	1.22	1.23	1.24	1.25
Compatibility	?	?	?	✓
✓ Fully supported version range.
? Due to breaking changes between Kubernetes API versions, some features might not work correctly in the Dashboard.
Images
Kubernetes Dashboard
docker.io/kubernetesui/dashboard:v2.7.0
Metrics Scraper
docker.io/kubernetesui/metrics-scraper:v1.0.8
Installation
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml
Contributors
@headcr4sh
@onestone9900
@shu-mutou
@korjek
@Seo-yul
@BrendenHJH
@rollony
@dewble
@gy-ulbak96
@jinnypark9393
@yuzin9712
@bconfiden2
@NayeonKeum
@having-dlrow
@elizaitsev
headcr4sh, onestone9900, and 13 other contributors
Assets 2
Source code
(zip)
Sep 16, 2022
Source code
(tar.gz)
Sep 16, 2022
13 people reacted
v2.6.1
Aug 12, 2022
@maciaszczykm maciaszczykm
 v2.6.1
 2ce9133
v2.6.1
What's Changed
add serviceMonitor labels/annotations by @TheRealNoob in #7120
Update Helm chart by @maciaszczykm in #7167
fix: close sizeChan to avoid memory leak. by @lixd in #7244
Use batch/v1 API & Add /health endpoint & Fix CronJob OwnerRef by @floreks in #7301
fix: fix panic while RsaKeyHolder secret is nil by @ismdeep in #7189
Set timeout in terminalSessions by @xuziheng1002 in #7314
Revert ng-in-viewport to 6.1.5 by @maciaszczykm in #7350
Show Capacity in the node list and node detail by @afbjorklund in #7111
Add barebones support for generic ephemeral volume by @cshubhamrao in #7093
Update Go version to 1.19 by @floreks in #7355
New Contributors
@TheRealNoob made their first contribution in #7120
@lixd made their first contribution in #7244
@ismdeep made their first contribution in #7189
@xuziheng1002 made their first contribution in #7314
@afbjorklund made their first contribution in #7111
@cshubhamrao made their first contribution in #7093
Full Changelog: v2.6.0...v2.6.1

Compatibility
Kubernetes version	1.21	1.22	1.23	1.24
Compatibility	?	?	?	✓
✓ Fully supported version range.
? Due to breaking changes between Kubernetes API versions, some features might not work correctly in the Dashboard.
Images
Kubernetes Dashboard
kubernetesui/dashboard:v2.6.1
Metrics Scraper
kubernetesui/metrics-scraper:v1.0.8
Installation
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.6.1/aio/deploy/recommended.yaml
Contributors
@floreks
@maciaszczykm
@cshubhamrao
@ismdeep
@afbjorklund
@TheRealNoob
@xuziheng1002
@lixd
floreks, maciaszczykm, and 6 other contributors
Assets 2
Source code
(zip)
Aug 12, 2022
Source code
(tar.gz)
Aug 12, 2022
4 people reacted
v2.6.0
May 31, 2022
@maciaszczykm maciaszczykm
 v2.6.0
 8cf47b5
v2.6.0
What's Changed
Added support for Kubernetes v1.24
Updated translations
Updated dependencies, workflows and project configs
fail to scrape metrics when use https by @drunkirishcoder in #6901
Added support for extra K8s manifests in the Helm chart by @andreadecorte in #6917
Pin actions to a full length commit SHA by @naveensrinivasan in #6910
ci(helm): remove local subchart tgz, upgrade helm ci dependencies, add gitignore for subcharts. by @desaintmartin in #6962
Remove ts-ignore and fix errors in dependencies by @xiaoyang-sde in #6976
Remove unused import and useless conditional expression by @xiaoyang-sde in #6971
Remove generic types from 'ResourceBase' to resolve failed test cases by @xiaoyang-sde in #6986
allow set custom clusterIP by @JoniJnm in #6953
Small Typo Fix by @zou-weidong in #6989
Implement the 'Preview' button and the 'Preview Deployment' dialog by @xiaoyang-sde in #6991
Normalize graph values after determining the highest suffix in the whole dataset by @jamesorlakin in #6952
Close subscription on destroy by @maciaszczykm in #6993
Update and fix issues with create from view by @floreks in #7007
Fix the problem that some place in the code can not be translated directly by @floreks in #6905
Styling adjustments and fixes by @maciaszczykm in #7008
Add support for IngressClass [#5232] by @andreadecorte in #6920
Update docs for 1.24+ by @liggitt in #6967
Full Changelog: v2.5.1...v2.6.0

New Contributors
@drunkirishcoder made their first contribution in #6901
@naveensrinivasan made their first contribution in #6910
@xiaoyang-sde made their first contribution in #6976
@JoniJnm made their first contribution in #6953
@zou-weidong made their first contribution in #6989
@jamesorlakin made their first contribution in #6952
@davidroth made their first contribution in #7117
@nathannaveen made their first contribution in #7036
Compatibility
Kubernetes version	1.21	1.22	1.23	1.24
Compatibility	?	?	?	✓
✓ Fully supported version range.
? Due to breaking changes between Kubernetes API versions, some features might not work correctly in the Dashboard.
Images
Kubernetes Dashboard
kubernetesui/dashboard:v2.6.0
Metrics Scraper
kubernetesui/metrics-scraper:v1.0.8
Installation
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.6.0/aio/deploy/recommended.yaml
Contributors
@desaintmartin
@andreadecorte
@naveensrinivasan
@davidroth
@drunkirishcoder
@JoniJnm
@liggitt
@floreks
@maciaszczykm
@jamesorlakin
@xiaoyang-sde
@zou-weidong
@nathannaveen
desaintmartin, andreadecorte, and 11 other contributors
Assets 2
Source code
(zip)
May 31, 2022
Source code
(tar.gz)
May 31, 2022
9 people reacted