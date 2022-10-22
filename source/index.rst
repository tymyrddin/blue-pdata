.. Data mitigations documentation master file, created by
   sphinx-quickstart on Sun Jun 26 04:55:59 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Protecting personal data
============================================

The Internet is rife with adversaries that are after our identity and information, and readily provides vulnerabilities that can be exploited for that. Some of the most common threats are software attacks, identity theft, theft of information, sabotage, information extortion, surveillance, censorship and data abuse for ever more profits and control. Many journalists, activists and researchers work have been exploited due to its vulnerable structure, sometimes with severe (life threatening) consequences.

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Goals

   docs/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Safer browsing

   docs/browsing/README.md
   docs/browsing/browsers.md
   docs/browsing/private-browsing.md
   docs/browsing/browser-config.md
   docs/browsing/browser-plugins.md
   docs/browsing/user-agent.md
   docs/browsing/cookies.md
   docs/browsing/FLoC.md
   docs/browsing/aif.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Anonymising traffic

   docs/traffic/README.md
   docs/traffic/tunnelling.md
   docs/traffic/ssh.md
   docs/traffic/vpn.md
   docs/traffic/vpn-fail-open.md
   docs/traffic/dns-leaks.md
   docs/traffic/digital-mixing.md
   docs/traffic/tor.md
   docs/traffic/i2p.md
   docs/traffic/chaining.md
   docs/traffic/vpn-ssh-tun.md
   docs/traffic/change-mac.md
   docs/traffic/renew-lease.md
   docs/traffic/change-nick.md
   docs/traffic/edit-hosts-file.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Securing email

   docs/email/README.md
   docs/email/email-services.md
   docs/email/email-use.md
   docs/email/check-mail.md
   docs/email/gnupg.md
   docs/email/hibp.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: E2EE messaging

   docs/e2ee/README.md
   docs/e2ee/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: File transfer

   docs/filetransfer/README.md
   docs/filetransfer/file-sharing-services.md
   docs/filetransfer/torrenting.md
   docs/filetransfer/sftp.md
   docs/filetransfer/integrity-downloads.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Data in rest

   docs/data/README.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Metadata

   docs/metadata/README.md
   docs/metadata/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Web applications

   docs/webapplication/README.md
   docs/webapplication/*

.. toctree::
   :caption: Links

   Blue Team <https://tymyrddin.github.io/blue/>
