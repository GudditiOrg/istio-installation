# Istio Installation Guide<img src="https://github.com/GudditiOrg/istio-installation/assets/87116202/2f9610f5-b69a-4824-84de-eaa2356c57a4" alt="image" width="10%" height="10%">



Are you curious about the magic behind those seamless web applications and services you use daily? Well, let's take a peek into the fascinating world of microservices and the tools that make them work like a charm: Istio, Kiali, Jaeger, Grafana, and Prometheus. These tools might sound a bit technical, but fear not! We're here to break it down in the simplest way possible.

## Install Istio
Istio is an open source service mesh that layers transparently onto existing distributed applications. Istio’s powerful features provide a uniform and more efficient way to secure, connect, and monitor services. Istio is the path to load balancing, service-to-service authentication, and monitoring – with few or no service code changes. 


The control plane takes your desired configuration, and its view of the services, and dynamically programs the proxy servers, updating them as the rules or the environment changes.
- Download the Istio distribution by following the instructions at https://istio.io/v1.16/docs/setup/install/istioctl/ and set up the PATH according.

## Install Kiali
Kiali is a console for Istio service mesh. Kiali can be quickly installed as an Istio add-on, or trusted as a part of your production environment.
- Install Kiali by using the following command: https://istio.io/latest/docs/tasks/observability/kiali/

## Install Jaeger
Jaeger is software that you can use to monitor and troubleshoot problems on interconnected software components called microservices. Several microservices communicate with each other to complete a single software function.
- Install Jaeger from the link: https://istio.io/latest/docs/ops/integrations/jaeger/

## Install Prometheus
Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources. 
- Install Prometheus using the guide: https://istio.io/latest/docs/ops/integrations/prometheus/

## Install Grafana
Prometheus is a free software application used for event monitoring and alerting. It records metrics in a time series database built using an HTTP pull model, with flexible queries and real-time alerting
- Install Grafana by following the steps at: https://istio.io/latest/docs/ops/integrations/grafana/

### Dashboards 
-  istioctl dashboard kiali &
-  istioctl dashboard grafana &
-  istioctl dashboard jaeger &
-  istioctl dashboard prometheus &

https://gnaganjaneyulu.blogspot.com/2023/08/introduction-to-istio-kiali-jaeger.html


