# ocp-ou
Openshift Observability UI Scripts and Wiki

## Planned Scripts Structure
2 primary actions

- Setting up external systems (oc apply -f or kubectl apply -f or **kubectl apply -k** or COO (like korrel8r))
  - Do what we have for now, then rework later
  - Single entry point (`make -logging -tempo`)
- Deploying local ones (path to your current code) (MAYBE or FUTURE) 

│ README.md
│ LICENSE
│ Makefile
└───setup (external components)
│   │   logging.yaml
│   │   loki.yaml
│   └───helm
│   │   │   tempo.idk
└───deploy
│   │   logging-view-plugin.sh
│   │   troubleshooting-panel.sh
│   │   ./monitoring-plugin.sh ~/Documents/projects/forks/monitoring-plugin


Planned Wiki Structure:
TBD
│ a file
│
└───something
