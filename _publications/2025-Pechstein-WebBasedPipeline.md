---
title: Web-based Pipeline Administration and Docker Remote Control for Extracting Open Access Journal Metadata
author: Pechstein, G., Müller, M., Kammer, D.
link: https://doi.org/10.69558/2026007
year: 2025
venue: Proceedings of the 28th Bilateral Student Workshop HTW Dresden and CTU Prague – User Interfaces & Visualization, pp. 31–39
type: workshop
tags: infovis
bibtex: >-
    @inproceedings{pechstein_remote_control2025,
        title = {Web-based Pipeline Administration and Docker Remote Control for Extracting Open Access Journal Metadata},
        url = {https://doi.org/10.69558/2026007},
        booktitle = {Proceedings of the 28th Bilateral Student Workshop HTW Dresden and CTU Prague – User Interfaces \& Visualization},
        author = {Pechstein, Gabriel and Müller, Mathias and Kammer, Dietrich},
        year = {2025},
        pages = {31–-39}
    }
---

This paper documents the implementation of a web-based administration dashboard for data extraction pipeline management. The system features an Angular frontend for process monitoring and a Proof of Concept (PoC) mechanism for remote container management. The Docker remote control subsystem exposes the Docker daemon’s REST API via an Nginx reverse proxy bridging HTTPS to the Unix socket. While the current implementation demonstrates functional feasibility, this paper proposes a rigorous security architecture for production deployment, recommending the integration of specialized socket proxies, mutual TLS authentication, and strict endpoint whitelisting to safely expose Docker management to browser clients.
