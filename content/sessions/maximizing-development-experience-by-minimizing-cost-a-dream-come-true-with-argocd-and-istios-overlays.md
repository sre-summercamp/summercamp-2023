---
key: maximizing-development-experience-by-minimizing-cost-a-dream-come-true-with-argocd-and-istios-overlays
title: "Maximizing development experience by minimizing cost: A dream come true with ArgoCD and Istio's overlays"
id: e5XJ3Vt7J59RhZvJYfuaUAzBqWdh
language: French
format: conference
tags:
  - _method___tools
level: intermediate
speakers:
  - sacha_bernheim
draft: false
videoId: N4v-mY7knxk
---
Companies struggle to provide an adequate development environment: rapid growth leads to a focus on production environments, while the developer teams scale at least as much the company and little to no effort is put on their daily work experience. An easy solution is to deploy a full application ecosystem for each developer, but it costs too much, so companies share those environments between developers. They should not.

As an ex-developer, I am convinced that each and every developer should be able to test new features without risking impacting other developers. As an SRE, I have been confronted to the creation of development environments for more than half a year.

In this talk, I will share:
- The use of ArgoCD for generating on-demand development environments and giving greater autonomy to your developers;
- The use of Istio and its overlays for minimizing the number of pods you need to deploy, routing a request to an application replica transparently in your development environments, and connecting those cloud environments to local computers;

When building on-demand development environments, I would have loved to be able to provide complete autonomy to developers by configuring network communications automatically. And I hope I can share how to do it with you!
