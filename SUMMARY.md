# [Istio 中文文档](https://github.com/istio/istio.io)

- Ambient
  - Architecture
    - Control Plane
      * [Ambient 和 Istio 控制平面](ambient/architecture/control-plane/index.md)
    - Data Plane
      * [Ambient 数据平面](ambient/architecture/data-plane/index.md)
    - Hbone
      * [HBONE](ambient/architecture/hbone/index.md)
    - Traffic Redirection
      * [ztunnel 流量重定向](ambient/architecture/traffic-redirection/index.md)
    * [架构](ambient/architecture/_index.md)
  - Getting Started
    - Cleanup
      * [清理](ambient/getting-started/cleanup/index.md)
    - Deploy Sample App
      * [部署示例应用程序](ambient/getting-started/deploy-sample-app/index.md)
    - Enforce Auth Policies
      * [执行鉴权政策](ambient/getting-started/enforce-auth-policies/index.md)
    - Manage Traffic
      * [管理流量](ambient/getting-started/manage-traffic/index.md)
    - Secure And Visualize
      * [保护和可视化应用程序](ambient/getting-started/secure-and-visualize/index.md)
    * [入门](ambient/getting-started/_index.md)
  - Install
    - Helm
      - All In One
        * [使用 Helm 安装（简易）](ambient/install/helm/all-in-one/index.md)
      * [通过 Helm 安装](ambient/install/helm/index.md)
    - Istioctl
      * [使用 istioctl 进行安装](ambient/install/istioctl/index.md)
    - Multicluster
      - Before You Begin
        * [开始之前](ambient/install/multicluster/before-you-begin/index.md)
      - Multi Primary Multi Network
        * [在不同的网络基础上安装 Ambient 多主模式](ambient/install/multicluster/multi-primary_multi-network/index.md)
      - Verify
        * [验证 Ambient 安装](ambient/install/multicluster/verify/index.md)
      * [安装多集群](ambient/install/multicluster/_index.md)
    - Platform Prerequisites
      * [平台特定的前提条件](ambient/install/platform-prerequisites/index.md)
    * [安装指南](ambient/install/_index.md)
  - Overview
    * [概述](ambient/overview/index.md)
  - Upgrade
    - Helm
      - All In One
        * [使用 Helm 升级（简易）](ambient/upgrade/helm/all-in-one/index.md)
      * [使用 Helm 升级](ambient/upgrade/helm/index.md)
    * [升级指南](ambient/upgrade/_index.md)
  - Usage
    - Add Workloads
      * [将工作负载添加到网格中](ambient/usage/add-workloads/index.md)
    - Extend Waypoint Wasm
      * [使用 WebAssembly 插件扩展 waypoint](ambient/usage/extend-waypoint-wasm/index.md)
    - L 4 Policy
      * [使用四层安全策略](ambient/usage/l4-policy/index.md)
    - L 7 Features
      * [使用七层功能](ambient/usage/l7-features/index.md)
    - Networkpolicy
      * [Ambient 和 Kubernetes NetworkPolicy](ambient/usage/networkpolicy/index.md)
    - Troubleshoot Waypoint
      * [waypoint 问题故障排除](ambient/usage/troubleshoot-waypoint/index.md)
    - Troubleshoot Ztunnel
      * [ztunnel 的连接问题排查](ambient/usage/troubleshoot-ztunnel/index.md)
    - Verify Mtls Enabled
      * [验证双向 TLS 已启用](ambient/usage/verify-mtls-enabled/index.md)
    - Waypoint
      * [配置 waypoint 代理](ambient/usage/waypoint/index.md)
    * [用户指南](ambient/usage/_index.md)
  * [Ambient 模式](ambient/_index.md)
- Concepts
  - Observability
    * [可观测性](concepts/observability/index.md)
  - Security
    * [安全](concepts/security/index.md)
  - Traffic Management
    * [流量管理](concepts/traffic-management/index.md)
  - Wasm
    * [扩展性](concepts/wasm/index.md)
  * [概念](concepts/_index.md)
- Examples
  - Bookinfo
    * [Bookinfo 应用](examples/bookinfo/index.md)
  - Microservices Istio
    - Add Istio
      * [在 productpage 启用 Istio](examples/microservices-istio/add-istio/index.md)
    - Add New Microservice Version
      * [添加一个新版本的 reviews](examples/microservices-istio/add-new-microservice-version/index.md)
    - Bookinfo Kubernetes
      * [使用 Kubernetes 运行 Bookinfo](examples/microservices-istio/bookinfo-kubernetes/index.md)
    - Enable Istio All Microservices
      * [在所有微服务上启用 Istio](examples/microservices-istio/enable-istio-all-microservices/index.md)
    - Istio Ingress Gateway
      * [配置 Istio Ingress Gateway](examples/microservices-istio/istio-ingress-gateway/index.md)
    - Logs Istio
      * [监控 Istio](examples/microservices-istio/logs-istio/index.md)
    - Package Service
      * [在 Docker 中运行 ratings 服务](examples/microservices-istio/package-service/index.md)
    - Prereq
      * [前提条件](examples/microservices-istio/prereq/index.md)
    - Production Testing
      * [生产测试](examples/microservices-istio/production-testing/index.md)
    - Setup Kubernetes Cluster
      * [设置 Kubernetes 集群](examples/microservices-istio/setup-kubernetes-cluster/index.md)
    - Setup Local Computer
      * [设置本地计算机](examples/microservices-istio/setup-local-computer/index.md)
    - Single
      * [本地运行微服务](examples/microservices-istio/single/index.md)
    * [使用 Kubernetes 和 Istio 学习微服务](examples/microservices-istio/_index.md)
  - Virtual Machines
    * [在虚拟机上部署 Bookinfo 应用程序](examples/virtual-machines/index.md)
  * [示例](examples/_index.md)
- Ops
  - Best Practices
    - Deployment
      * [Deployment 最佳实践](ops/best-practices/deployment/index.md)
    - Image Signing Validation
      * [镜像签名和验证](ops/best-practices/image-signing-validation/index.md)
    - Observability
      * [可观测性最佳实践](ops/best-practices/observability/index.md)
    - Security
      * [安全最佳实践](ops/best-practices/security/index.md)
    - Traffic Management
      * [流量管理最佳实践](ops/best-practices/traffic-management/index.md)
    * [最佳实践](ops/best-practices/_index.md)
  - Common Problems
    - Injection
      * [Sidecar 自动注入问题](ops/common-problems/injection/index.md)
    - Network Issues
      * [流量管理问题](ops/common-problems/network-issues/index.md)
    - Observability Issues
      * [可观测性问题](ops/common-problems/observability-issues/index.md)
    - Security Issues
      * [安全问题](ops/common-problems/security-issues/index.md)
    - Upgrade Issues
      * [升级问题](ops/common-problems/upgrade-issues/index.md)
    - Validation
      * [配置验证的问题](ops/common-problems/validation/index.md)
    * [常见问题](ops/common-problems/_index.md)
  - Configuration
    - Extensibility
      - Wasm Pull Policy
        * [WebAssembly 模块的拉取策略](ops/configuration/extensibility/wasm-pull-policy/index.md)
      * [可扩展性](ops/configuration/extensibility/_index.md)
    - Mesh
      - App Health Check
        * [Istio 服务的健康检查](ops/configuration/mesh/app-health-check/index.md)
      - Configuration Scoping
        * [配置范围](ops/configuration/mesh/configuration-scoping/index.md)
      - Webhook
        * [动态准入 Webhook 概述](ops/configuration/mesh/webhook/index.md)
      * [网格配置](ops/configuration/mesh/_index.md)
    - Security
      - Harden Docker Images
        * [加固 Docker 容器镜像](ops/configuration/security/harden-docker-images/index.md)
      - Security Policy Examples
        * [安全策略示例](ops/configuration/security/security-policy-examples/index.md)
      * [安全](ops/configuration/security/_index.md)
    - Telemetry
      - Envoy Stats
        * [Envoy 的统计信息](ops/configuration/telemetry/envoy-stats/index.md)
      - Monitoring Multicluster Prometheus
        * [使用 Prometheus 监控 Istio 多集群](ops/configuration/telemetry/monitoring-multicluster-prometheus/index.md)
      * [可观测性](ops/configuration/telemetry/_index.md)
    - Traffic Management
      - Dns
        * [理解 DNS](ops/configuration/traffic-management/dns/index.md)
      - Dns Proxy
        * [DNS 代理](ops/configuration/traffic-management/dns-proxy/index.md)
      - Manage Mesh Certificates
        * [管理网格内证书](ops/configuration/traffic-management/manage-mesh-certificates/index.md)
      - Multicluster
        * [多集群流量管理](ops/configuration/traffic-management/multicluster/index.md)
      - Network Topologies
        * [配置 Gateway 网络拓扑](ops/configuration/traffic-management/network-topologies/index.md)
      - Protocol Selection
        * [协议选择](ops/configuration/traffic-management/protocol-selection/index.md)
      - Tls Configuration
        * [理解 TLS 配置](ops/configuration/traffic-management/tls-configuration/index.md)
      - Traffic Routing
        * [了解流量路由](ops/configuration/traffic-management/traffic-routing/index.md)
      * [流量管理](ops/configuration/traffic-management/_index.md)
    * [配置](ops/configuration/_index.md)
  - Deployment
    - Ambient Mc Perf
      * [Ambient 多集群性能](ops/deployment/ambient-mc-perf/index.md)
    - Application Requirements
      * [应用程序要求](ops/deployment/application-requirements/index.md)
    - Architecture
      - Cni
        * [CNI 插件](ops/deployment/architecture/cni/index.md)
      * [架构](ops/deployment/architecture/index.md)
    - Deployment Models
      * [部署模型](ops/deployment/deployment-models/index.md)
    - Performance And Scalability
      * [性能和可扩展性](ops/deployment/performance-and-scalability/index.md)
    - Platform Requirements
      * [平台要求](ops/deployment/platform-requirements/index.md)
    - Security Model
      * [安全模型](ops/deployment/security-model/index.md)
    - Vm Architecture
      * [虚拟机架构](ops/deployment/vm-architecture/index.md)
    * [部署](ops/deployment/_index.md)
  - Diagnostic Tools
    - Check Inject
      * [使用 istioctl check-inject 验证 Istio Sidecar 注入](ops/diagnostic-tools/check-inject/index.md)
    - Cni
      * [Istio CNI 插件故障排除](ops/diagnostic-tools/cni/index.md)
    - Component Logging
      * [组件日志记录](ops/diagnostic-tools/component-logging/index.md)
    - Controlz
      * [组件自检](ops/diagnostic-tools/controlz/index.md)
    - Istioctl
      * [使用 Istioctl 命令行工具](ops/diagnostic-tools/istioctl/index.md)
    - Istioctl Analyze
      * [使用 istioctl analyze 诊断配置](ops/diagnostic-tools/istioctl-analyze/index.md)
    - Istioctl Describe
      * [通过 istioctl describe 检查您的网格](ops/diagnostic-tools/istioctl-describe/index.md)
    - Multicluster
      * [多集群下的故障排除](ops/diagnostic-tools/multicluster/index.md)
    - Proxy Cmd
      * [调试 Envoy 和 Istiod](ops/diagnostic-tools/proxy-cmd/index.md)
    - Virtual Machines
      * [虚拟机调试](ops/diagnostic-tools/virtual-machines/index.md)
    * [诊断工具](ops/diagnostic-tools/_index.md)
  - Integrations
    - Certmanager
      * [Cert Manager](ops/integrations/certmanager/index.md)
    - Grafana
      * [Grafana](ops/integrations/grafana/index.md)
    - Jaeger
      * [Jaeger](ops/integrations/jaeger/index.md)
    - Kiali
      * [Kiali](ops/integrations/kiali/index.md)
    - Loadbalancers
      * [第三方负载均衡器](ops/integrations/loadbalancers/index.md)
    - Prometheus
      * [Prometheus](ops/integrations/prometheus/index.md)
    - Skywalking
      * [Apache Sky Walking](ops/integrations/skywalking/index.md)
    - Spire
      * [SPIRE](ops/integrations/spire/index.md)
    - Zipkin
      * [Zipkin](ops/integrations/zipkin/index.md)
    * [集成](ops/integrations/_index.md)
  * [运维](ops/_index.md)
- Overview
  - Dataplane Modes
    * [Sidecar 还是 Ambient？](overview/dataplane-modes/index.md)
  - Quickstart
    * [快速入门](overview/quickstart/index.md)
  - What Is Istio
    * [Istio 是什么？](overview/what-is-istio/index.md)
  - Why Choose Istio
    * [为什么选择 Istio？](overview/why-choose-istio/index.md)
  * [概述](overview/_index.md)
- Reference
  - Commands
    * [命令](reference/commands/_index.md)
  - Config
    - Analysis
      - Ist 0001
        * [Internal Error](reference/config/analysis/ist0001/index.md)
      - Ist 0002
        * [Deprecated](reference/config/analysis/ist0002/index.md)
      - Ist 0101
        * [Referenced Resource Not Found](reference/config/analysis/ist0101/index.md)
      - Ist 0102
        * [Namespace Not Injected](reference/config/analysis/ist0102/index.md)
      - Ist 0103
        * [Pod Missing Proxy](reference/config/analysis/ist0103/index.md)
      - Ist 0106
        * [Schema Validation Error](reference/config/analysis/ist0106/index.md)
      - Ist 0107
        * [Misplaced Annotation](reference/config/analysis/ist0107/index.md)
      - Ist 0108
        * [Unknown Annotation](reference/config/analysis/ist0108/index.md)
      - Ist 0109
        * [Conflicting Mesh Gateway Virtual Service Hosts](reference/config/analysis/ist0109/index.md)
      - Ist 0110
        * [Conflicting Sidecar Workload Selectors](reference/config/analysis/ist0110/index.md)
      - Ist 0111
        * [Multiple Sidecars Without Workload Selectors](reference/config/analysis/ist0111/index.md)
      - Ist 0112
        * [Virtual Service Destination Port Selector Required](reference/config/analysis/ist0112/index.md)
      - Ist 0116
        * [Deployment Associated To Multiple Services](reference/config/analysis/ist0116/index.md)
      - Ist 0118
        * [Port Name Is Not Under Naming Convention](reference/config/analysis/ist0118/index.md)
      - Ist 0123
        * [Namespace Multiple Injection Labels](reference/config/analysis/ist0123/index.md)
      - Ist 0125
        * [Invalid Annotation](reference/config/analysis/ist0125/index.md)
      - Ist 0127
        * [No Matching Workloads Found](reference/config/analysis/ist0127/index.md)
      - Ist 0128
        * [No Server Certificate Verification Destination Level](reference/config/analysis/ist0128/index.md)
      - Ist 0129
        * [No Server Certificate Verification Port Level](reference/config/analysis/ist0129/index.md)
      - Ist 0130
        * [Virtual Service Unreachable Rule](reference/config/analysis/ist0130/index.md)
      - Ist 0131
        * [Virtual Service Ineffective Match](reference/config/analysis/ist0131/index.md)
      - Ist 0132
        * [Virtual Service Host Not Found In Gateway](reference/config/analysis/ist0132/index.md)
      - Ist 0134
        * [Service Entry Addresses Required](reference/config/analysis/ist0134/index.md)
      - Ist 0135
        * [Deprecated Annotation](reference/config/analysis/ist0135/index.md)
      - Ist 0136
        * [Alpha Annotation](reference/config/analysis/ist0136/index.md)
      - Ist 0137
        * [Deployment Conflicting Ports](reference/config/analysis/ist0137/index.md)
      - Ist 0143
        * [Localhost Listener](reference/config/analysis/ist0143/index.md)
      - Ist 0144
        * [Invalid Application UID](reference/config/analysis/ist0144/index.md)
      - Ist 0150
        * [External Name Service Type Invalid Port Name](reference/config/analysis/ist0150/index.md)
      - Ist 0151
        * [Envoy Filter Uses Relative Operation](reference/config/analysis/ist0151/index.md)
      - Ist 0152
        * [Envoy Filter Uses Replace Operation Incorrectly](reference/config/analysis/ist0152/index.md)
      - Ist 0153
        * [Envoy Filter Uses Add Operation Incorrectly](reference/config/analysis/ist0153/index.md)
      - Ist 0154
        * [Envoy Filter Uses Remove Operation Incorrectly](reference/config/analysis/ist0154/index.md)
      - Ist 0155
        * [Envoy Filter Uses Relative Operation With Proxy Version](reference/config/analysis/ist0155/index.md)
      - Ist 0157
        * [Invalid Telemetry Provider](reference/config/analysis/ist0157/index.md)
      - Ist 0158
        * [Pods Istio Proxy Image Mismatch In Namespace](reference/config/analysis/ist0158/index.md)
      - Ist 0159
        * [Conflicting Telemetry Workload Selectors](reference/config/analysis/ist0159/index.md)
      - Ist 0160
        * [Multiple Telemetries Without Workload Selectors](reference/config/analysis/ist0160/index.md)
      - Ist 0161
        * [Invalid Gateway Credential](reference/config/analysis/ist0161/index.md)
      - Ist 0162
        * [Gateway Port Not Defined On Service](reference/config/analysis/ist0162/index.md)
      - Ist 0163
        * [Invalid External Control Plane Config](reference/config/analysis/ist0163/index.md)
      - Ist 0164
        * [External Control Plane Address Is Not A Hostname](reference/config/analysis/ist0164/index.md)
      - Ist 0166
        * [Ineffective Selector](reference/config/analysis/ist0166/index.md)
      - Ist 0167
        * [Ineffective Policy](reference/config/analysis/ist0167/index.md)
      - Message Format
        * [Analyzer Message Format](reference/config/analysis/message-format/index.md)
      * [配置分析消息](reference/config/analysis/_index.md)
    - Config Status
      * [状态字段配置](reference/config/config-status/index.md)
    - Metrics
      * [Istio 标准指标](reference/config/metrics/index.md)
    - Networking
      * [流量管理](reference/config/networking/_index.md)
    - Proxy Extensions
      * [代理扩展](reference/config/proxy_extensions/_index.md)
    - Security
      - Conditions
        * [授权策略](reference/config/security/conditions/index.md)
      - Normalization
        * [授权策略规范化](reference/config/security/normalization/index.md)
      * [Security](reference/config/security/_index.md)
    - Type
      * [常见类型](reference/config/type/_index.md)
    * [配置](reference/config/_index.md)
  - Glossary
    * [Ambient](reference/glossary/ambient.md)
    * [Annotation](reference/glossary/annotation.md)
    * [Attribute](reference/glossary/attribute.md)
    * [自动 mTLS](reference/glossary/auto-mtls.md)
    * [Cluster](reference/glossary/cluster.md)
    * [CNI](reference/glossary/cni.md)
    * [Control Plane](reference/glossary/control-plane.md)
    * [CRD](reference/glossary/crds.md)
    * [Data Plane](reference/glossary/data-plane.md)
    * [Data Plane Mode](reference/glossary/dataplane-mode.md)
    * [Destination](reference/glossary/destination.md)
    * [E BPF](reference/glossary/ebpf.md)
    * [Envoy](reference/glossary/envoy.md)
    * [External Control Plane](reference/glossary/external-control-plane.md)
    * [Failure Domain](reference/glossary/failure-domain.md)
    * [Gateway API](reference/glossary/gateway-api.md)
    * [Gateway](reference/glossary/gateway.md)
    * [HBONE](reference/glossary/hbone.md)
    * [Identity](reference/glossary/identity.md)
    * [术语表](reference/glossary/index.md)
    * [Injection](reference/glossary/injection.md)
    * [IO](reference/glossary/io.md)
    * [IOP](reference/glossary/iop.md)
    * [Istio Operator Custom Resource](reference/glossary/istio-operator-custom-resource.md)
    * [Istiod](reference/glossary/istiod.md)
    * [Managed Control Plane](reference/glossary/managed-control-plane.md)
    * [Mesh Federation](reference/glossary/mesh-federation.md)
    * [Micro Segmentation](reference/glossary/micro-segmentation.md)
    * [Multi Mesh](reference/glossary/multi-mesh.md)
    * [Multicluster](reference/glossary/multicluster.md)
    * [Mutual TLS Authentication](reference/glossary/mutual-tls.md)
    * [Namespace Sameness](reference/glossary/namespace-sameness.md)
    * [Network](reference/glossary/network.md)
    * [Operator](reference/glossary/operator.md)
    * [Pilot](reference/glossary/pilot.md)
    * [Pod](reference/glossary/pod.md)
    * [Primary Cluster](reference/glossary/primary-cluster.md)
    * [Proxyless](reference/glossary/proxyless.md)
    * [Remote Cluster](reference/glossary/remote-cluster.md)
    * [Routing Rules](reference/glossary/routing-rules.md)
    * [Secure L 4 Overlay](reference/glossary/secure-l4-overlay.md)
    * [Secure Naming](reference/glossary/secure-naming.md)
    * [Service Consumer](reference/glossary/service-consumer.md)
    * [Service Endpoint](reference/glossary/service-endpoint.md)
    * [Service Mesh](reference/glossary/service-mesh.md)
    * [Service Name](reference/glossary/service-name.md)
    * [Service Operator](reference/glossary/service-operator.md)
    * [Service Producer](reference/glossary/service-producer.md)
    * [Service Registry](reference/glossary/service-registry.md)
    * [Service Version](reference/glossary/service-version.md)
    * [Service](reference/glossary/service.md)
    * [Sidecar](reference/glossary/sidecar.md)
    * [Source](reference/glossary/source.md)
    * [SPIFFE](reference/glossary/spiffe.md)
    * [TLS Origination](reference/glossary/tls-origination.md)
    * [Trust Domain Migration](reference/glossary/trust-domain-migration.md)
    * [Trust Domain](reference/glossary/trust-domain.md)
    * [Waypoint](reference/glossary/waypoint.md)
    * [Workload Instance Principal](reference/glossary/workload-instance-principal.md)
    * [Workload Instance](reference/glossary/workload-instance.md)
    * [Workload](reference/glossary/workload.md)
    * [Ztunnel](reference/glossary/ztunnel.md)
  * [参考](reference/_index.md)
- Releases
  - Bugs
    * [报告错误](releases/bugs/index.md)
  - Contribute
    - Add Content
      * [添加新文档](releases/contribute/add-content/index.md)
    - Build
      * [本地构建和运行本网站](releases/contribute/build/index.md)
    - Code Blocks
      * [添加代码块](releases/contribute/code-blocks/index.md)
    - Diagrams
      * [创建图表指南](releases/contribute/diagrams/index.md)
    - Formatting
      * [格式标准](releases/contribute/formatting/index.md)
    - Front Matter
      * [文章头部](releases/contribute/front-matter/index.md)
    - Github
      * [使用 GitHub 参与社区活动](releases/contribute/github/index.md)
    - Remove Content
      * [删除已停用的文档](releases/contribute/remove-content/index.md)
    - Review
      * [文档审阅流程](releases/contribute/review/index.md)
    - Shortcodes
      * [使用 Shortcode](releases/contribute/shortcodes/index.md)
    - Style Guide
      * [风格指南](releases/contribute/style-guide/index.md)
    - Terminology
      * [术语标准](releases/contribute/terminology/index.md)
    * [贡献文档](releases/contribute/_index.md)
  - Feature Stages
    * [功能状态](releases/feature-stages/index.md)
  - Log
    * [网站内容更改](releases/log/index.md)
  - Security Vulnerabilities
    * [安全漏洞](releases/security-vulnerabilities/index.md)
  - Supported Releases
    * [版本支持](releases/supported-releases/index.md)
  * [发布](releases/_index.md)
- Setup
  - Additional Setup
    - Cni
      * [安装 Istio CNI 节点代理](setup/additional-setup/cni/index.md)
    - Compatibility Versions
      * [兼容版本](setup/additional-setup/compatibility-versions/index.md)
    - Config Profiles
      * [安装配置文件](setup/additional-setup/config-profiles/index.md)
    - Customize Installation
      * [定制安装配置](setup/additional-setup/customize-installation/index.md)
    - Customize Installation Helm
      * [高级 Helm chart 自定义](setup/additional-setup/customize-installation-helm/index.md)
    - Download Istio Release
      * [下载 Istio 发行版](setup/additional-setup/download-istio-release/index.md)
    - Dual Stack
      * [在双栈模式中安装 Istio](setup/additional-setup/dual-stack/index.md)
    - Gateway
      * [安装 Gateway](setup/additional-setup/gateway/index.md)
    - Getting Started Istio Apis
      * [无需 Gateway API 开始使用](setup/additional-setup/getting-started-istio-apis/index.md)
    - Pod Security Admission
      * [通过 Pod 安全准入安装 Istio](setup/additional-setup/pod-security-admission/index.md)
    - Sidecar Injection
      * [安装 Sidecar](setup/additional-setup/sidecar-injection/index.md)
    * [更多指南](setup/additional-setup/_index.md)
  - Getting Started
    * [入门](setup/getting-started/index.md)
  - Install
    - External Controlplane
      * [使用外部控制平面安装 Istio](setup/install/external-controlplane/index.md)
    - Helm
      * [使用 Helm 安装](setup/install/helm/index.md)
    - Istioctl
      * [使用 Istioctl 安装](setup/install/istioctl/index.md)
    - Multicluster
      - Before You Begin
        * [准备工作](setup/install/multicluster/before-you-begin/index.md)
      - Multi Primary
        * [多主架构的安装](setup/install/multicluster/multi-primary/index.md)
      - Multi Primary Multi Network
        * [跨网络多主架构的安装](setup/install/multicluster/multi-primary_multi-network/index.md)
      - Primary Remote
        * [主从架构的安装](setup/install/multicluster/primary-remote/index.md)
      - Primary Remote Multi Network
        * [跨网络安装主从集群](setup/install/multicluster/primary-remote_multi-network/index.md)
      - Verify
        * [验证安装结果](setup/install/multicluster/verify/index.md)
      * [多集群安装](setup/install/multicluster/_index.md)
    - Multiple Controlplanes
      * [在单集群中安装多个 Istio 控制面](setup/install/multiple-controlplanes/index.md)
    - Virtual Machine
      * [虚拟机安装](setup/install/virtual-machine/index.md)
    * [安装指南](setup/install/_index.md)
  - Platform Setup
    - Alicloud
      * [阿里云](setup/platform-setup/alicloud/index.md)
    - Amazon Eks
      * [Amazon EKS](setup/platform-setup/amazon-eks/index.md)
    - Azure
      * [Azure](setup/platform-setup/azure/index.md)
    - Docker
      * [Docker Desktop](setup/platform-setup/docker/index.md)
    - Gardener
      * [Kubernetes Gardener 快速开始](setup/platform-setup/gardener/index.md)
    - Gke
      * [使用 Google Kubernetes Engine 快速开始](setup/platform-setup/gke/index.md)
    - Huaweicloud
      * [华为云](setup/platform-setup/huaweicloud/index.md)
    - Ibm
      * [IBM Cloud 快速开始](setup/platform-setup/ibm/index.md)
    - [K 3 D](setup/platform-setup/k3d/index.md)
    - [Kind](setup/platform-setup/kind/index.md)
    - Kops
      * [Kops](setup/platform-setup/kops/index.md)
    - Kubesphere
      * [Kube Sphere Container Platform](setup/platform-setup/kubesphere/index.md)
    - [Micro K 8 S](setup/platform-setup/MicroK8s/index.md)
    - [Minikube](setup/platform-setup/minikube/index.md)
    - Oci
      * [Oracle Cloud 基础架构](setup/platform-setup/oci/index.md)
    - Openshift
      * [Open Shift](setup/platform-setup/openshift/index.md)
    - Tencent Cloud Mesh
      * [腾讯云](setup/platform-setup/tencent-cloud-mesh/index.md)
    * [平台安装](setup/platform-setup/_index.md)
  - Upgrade
    - Canary
      * [金丝雀升级](setup/upgrade/canary/index.md)
    - Helm
      * [使用 Helm 升级](setup/upgrade/helm/index.md)
    - In Place
      * [原地升级](setup/upgrade/in-place/index.md)
    * [升级 Istio](setup/upgrade/_index.md)
  * [Sidecar 模式](setup/_index.md)
- Tasks
  - Extensibility
    - Wasm Module Distribution
      * [WebAssembly 模块分发](tasks/extensibility/wasm-module-distribution/index.md)
    * [可扩展性](tasks/extensibility/_index.md)
  - Observability
    - Distributed Tracing
      - Jaeger
        * [Jaeger](tasks/observability/distributed-tracing/jaeger/index.md)
      - Mesh And Proxy Config
        * [使用 MeshConfig 和 Pod 注解配置链路追踪](tasks/observability/distributed-tracing/mesh-and-proxy-config/index.md)
      - Opentelemetry
        * [Open Telemetry](tasks/observability/distributed-tracing/opentelemetry/index.md)
      - Overview
        * [概述](tasks/observability/distributed-tracing/overview/index.md)
      - Sampling
        * [配置链路采样](tasks/observability/distributed-tracing/sampling/index.md)
      - Skywalking
        * [Apache Sky Walking](tasks/observability/distributed-tracing/skywalking/index.md)
      - Telemetry Api
        * [使用 Telemetry API 配置链路追踪](tasks/observability/distributed-tracing/telemetry-api/index.md)
      - Zipkin
        * [Zipkin](tasks/observability/distributed-tracing/zipkin/index.md)
      * [分布式追踪](tasks/observability/distributed-tracing/_index.md)
    - Gateways
      * [远程访问遥测插件](tasks/observability/gateways/index.md)
    - Kiali
      * [网格可视化](tasks/observability/kiali/index.md)
    - Logs
      - Access Log
        * [获取 Envoy 访问日志](tasks/observability/logs/access-log/index.md)
      - Otel Provider
        * [Open Telemetry](tasks/observability/logs/otel-provider/index.md)
      - Telemetry Api
        * [使用 Telemetry API 配置访问日志](tasks/observability/logs/telemetry-api/index.md)
      * [日志](tasks/observability/logs/_index.md)
    - Metrics
      - Classify Metrics
        * [根据请求或响应对指标进行分类](tasks/observability/metrics/classify-metrics/index.md)
      - Customize Metrics
        * [自定义 Istio 指标](tasks/observability/metrics/customize-metrics/index.md)
      - Querying Metrics
        * [通过 Prometheus 查询度量指标](tasks/observability/metrics/querying-metrics/index.md)
      - Tcp Metrics
        * [收集 TCP 服务指标](tasks/observability/metrics/tcp-metrics/index.md)
      - Telemetry Api
        * [使用 Telemetry API 自定义 Istio 监控指标](tasks/observability/metrics/telemetry-api/index.md)
      - Using Istio Dashboard
        * [使用 Grafana 可视化指标](tasks/observability/metrics/using-istio-dashboard/index.md)
      * [指标](tasks/observability/metrics/_index.md)
    - Telemetry
      * [Telemetry API](tasks/observability/telemetry/index.md)
    * [可观测性](tasks/observability/_index.md)
  - Policy Enforcement
    - Rate Limit
      * [使用 Envoy 启用速率限制](tasks/policy-enforcement/rate-limit/index.md)
    * [策略执行](tasks/policy-enforcement/_index.md)
  - Security
    - Authentication
      - Authn Policy
        * [认证策略](tasks/security/authentication/authn-policy/index.md)
      - Claim To Header
        * [复制 JWT 声明到 HTTP 头](tasks/security/authentication/claim-to-header/index.md)
      - Jwt Route
        * [基于 JWT 声明的路由](tasks/security/authentication/jwt-route/index.md)
      - Mtls Migration
        * [双向 TLS 迁移](tasks/security/authentication/mtls-migration/index.md)
      * [认证](tasks/security/authentication/_index.md)
    - Authorization
      - Authz Custom
        * [外部授权](tasks/security/authorization/authz-custom/index.md)
      - Authz Deny
        * [明确拒绝](tasks/security/authorization/authz-deny/index.md)
      - Authz Dry Run
        * [模拟运行](tasks/security/authorization/authz-dry-run/index.md)
      - Authz Http
        * [HTTP 流量](tasks/security/authorization/authz-http/index.md)
      - Authz Ingress
        * [Ingress 网关](tasks/security/authorization/authz-ingress/index.md)
      - Authz Jwt
        * [JWT 令牌](tasks/security/authorization/authz-jwt/index.md)
      - Authz Tcp
        * [TCP 流量](tasks/security/authorization/authz-tcp/index.md)
      - Authz Td Migration
        * [信任域迁移](tasks/security/authorization/authz-td-migration/index.md)
      * [授权](tasks/security/authorization/_index.md)
    - Cert Management
      - Custom Ca K 8 S
        * [使用 Kubernetes CSR 自定义 CA 集成](tasks/security/cert-management/custom-ca-k8s/index.md)
      - Plugin Ca Cert
        * [插入 CA 证书](tasks/security/cert-management/plugin-ca-cert/index.md)
      * [证书管理](tasks/security/cert-management/_index.md)
    - Tls Configuration
      - Workload Min Tls Version
        * [Istio 工作负载的最低 TLS 版本配置](tasks/security/tls-configuration/workload-min-tls-version/index.md)
      * [TLS 配置](tasks/security/tls-configuration/_index.md)
    * [安全](tasks/security/_index.md)
  - Traffic Management
    - Circuit Breaking
      * [熔断](tasks/traffic-management/circuit-breaking/index.md)
    - Egress
      - Egress Control
        * [访问外部服务](tasks/traffic-management/egress/egress-control/index.md)
      - Egress Gateway
        * [Egress 网关](tasks/traffic-management/egress/egress-gateway/index.md)
      - Egress Gateway Tls Origination
        * [Egress 网关的 TLS 发起过程](tasks/traffic-management/egress/egress-gateway-tls-origination/index.md)
      - Egress Kubernetes Services
        * [Kubernetes 出口流量服务](tasks/traffic-management/egress/egress-kubernetes-services/index.md)
      - Egress Tls Origination
        * [Egress TLS 源](tasks/traffic-management/egress/egress-tls-origination/index.md)
      - Http Proxy
        * [使用外部 HTTPS 代理](tasks/traffic-management/egress/http-proxy/index.md)
      - Wildcard Egress Hosts
        * [Wildcard 主机的 Egress](tasks/traffic-management/egress/wildcard-egress-hosts/index.md)
      * [Egress](tasks/traffic-management/egress/_index.md)
    - Fault Injection
      * [故障注入](tasks/traffic-management/fault-injection/index.md)
    - Ingress
      - Gateway Api
        * [Kubernetes Gateway API](tasks/traffic-management/ingress/gateway-api/index.md)
      - Ingress Control
        * [Ingress 网关](tasks/traffic-management/ingress/ingress-control/index.md)
      - Ingress Sidecar Tls Termination
        * [Ingress Sidecar TLS 终止](tasks/traffic-management/ingress/ingress-sidecar-tls-termination/index.md)
      - Ingress Sni Passthrough
        * [无 TLS 终止的 Ingress Gateway](tasks/traffic-management/ingress/ingress-sni-passthrough/index.md)
      - Kubernetes Ingress
        * [Kubernetes Ingress](tasks/traffic-management/ingress/kubernetes-ingress/index.md)
      - Secure Ingress
        * [安全网关](tasks/traffic-management/ingress/secure-ingress/index.md)
      * [Ingress](tasks/traffic-management/ingress/_index.md)
    - Locality Load Balancing
      - Before You Begin
        * [开始之前](tasks/traffic-management/locality-load-balancing/before-you-begin/index.md)
      - Cleanup
        * [清理](tasks/traffic-management/locality-load-balancing/cleanup/index.md)
      - Distribute
        * [地域权重分布](tasks/traffic-management/locality-load-balancing/distribute/index.md)
      - Failover
        * [地域故障转移](tasks/traffic-management/locality-load-balancing/failover/index.md)
      * [地域负载均衡](tasks/traffic-management/locality-load-balancing/_index.md)
    - Mirroring
      * [镜像](tasks/traffic-management/mirroring/index.md)
    - Request Routing
      * [配置请求路由](tasks/traffic-management/request-routing/index.md)
    - Request Timeouts
      * [设置请求超时](tasks/traffic-management/request-timeouts/index.md)
    - Tcp Traffic Shifting
      * [TCP 流量转移](tasks/traffic-management/tcp-traffic-shifting/index.md)
    - Traffic Shifting
      * [流量转移](tasks/traffic-management/traffic-shifting/index.md)
    * [流量管理](tasks/traffic-management/_index.md)
  * [任务](tasks/_index.md)
* [文档](README.md)
