# Aleksander Szczygielski

**Electronics & Telecommunications engineer (M.Eng. student @ AGH Kraków) who builds software across the stack - web, embedded, and the CI/CD in between.**

I like owning things end-to-end: my club's website runs in production on code, infrastructure, and deployment pipelines I built solo, and my engineering thesis put a custom-trained vision model on a Raspberry Pi in a 3D-printed enclosure. Currently looking for a **software engineering internship / working-student role**.

Kraków, Poland · [LinkedIn](www.linkedin.com/in/aleksander-szczygielski-505821367)

---

## Featured: production system I run solo

**[argo_website](https://github.com/AlexSzczygielski/argo_website)** — live at [argo.agh.edu.pl](https://argo.agh.edu.pl)

Website + custom CMS for the AGH sailing club I founded and preside over. Vanilla PHP + MySQL: bcrypt auth, role-based draft→approval→publish workflow, rich-text editing with live preview, hardened image-upload pipeline. Deployed by GitHub Actions **through an OpenVPN tunnel** into the university network, with a **PR-gated reverse sync** so the CMS publishes content without ever touching git.

`PHP` `MySQL` `JavaScript` `GitHub Actions` `OpenVPN` `rsync`

## Other projects

| Project | What it is | Stack |
|---|---|---|
| [navigation-and-weather-device](https://github.com/AlexSzczygielski/navigation-and-weather-device-enhancing-the-safety-of-amateur-inland-navigation) | **Engineering thesis** — open-source IoT navigation & safety device for inland sailing: GPS + offline maps, live weather, and a custom-trained YOLO **Man Overboard detection** model. Unit tests, UML docs, CI. | `Python` `PyQt5/QML` `YOLO` `Raspberry Pi` |
| [vps-wake-on-lan-no-ssh](https://github.com/AlexSzczygielski/vps-wake-on-lan-no-ssh) | Remote power-on for a home PC via a VPS relay — **zero open ports** on the home network. Flask REST backend, systemd-managed daemons. | `Python` `Flask` `Linux` `systemd` |
| [custom-knn](https://github.com/AlexSzczygielski/custom-knn) | k-NN classifier from scratch, benchmarked against scikit-learn; packaged with PyScaffold, tested with pytest in CI. | `Python` `NumPy` `pytest` |
| [first-model-omega-boat-deck](https://github.com/AlexSzczygielski/first-model-omega-boat-deck) | First custom YOLO segmentation model — detecting boat decks in photos, trained in Colab. | `Python` `YOLO` `Colab` |
| [fpga-rsa-key-generation](https://github.com/AlexSzczygielski/fpga-rsa-key-generation) | RSA key generation in hardware — coursework from the EE side of my degree. | `FPGA` `HDL` |

## Experience

- **Software Developer Intern @ [CTI](https://cti.org.pl)** (2025) — internal PHP/MySQL web app hardened against SQL injection; C# tool exporting 23M-row SQL Server datasets to XML with a streaming architecture that cut peak RAM **9×**
- **IT Dept. @ [AGH Rapid Prototyping](https://github.com/AGHRapidPro)** (student research club) — Linux server + WordPress administration, GitHub Actions deploy workflows, Dockerized scheduled router-config backups
- **Founder & President @ SKR Argo AGH** (2024–) — built the club and its infrastructure from zero

## Tools I reach for

`Python` `PHP` `C#` `C++` `SQL (MySQL/SQLite)` `Bash` `JavaScript` · `Git` `Docker` `GitHub Actions` `Linux` · `Raspberry Pi` `FPGA`

---

<details>
<summary>⛵ Off the keyboard</summary>

Sailing coach and instructor since 2021; I compete for AGH in national academic sailing championships (plus skiing and track & field). Most of my projects exist because something on the water needed solving.

</details>

<!-- Optional: GitHub stats card — uncomment if you like the look
![Stats](https://github-readme-stats.vercel.app/api?username=AlexSzczygielski&show_icons=true&theme=default&rank_icon=github)
-->
