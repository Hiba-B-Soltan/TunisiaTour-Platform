<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=800&color=0A9396&background=FFFFFF00&center=true&vCenter=true&width=800&lines=A+COUNTRY.;A+CLOUD.;A+CHALLENGE.;TUNISIATOUR." alt="Typing SVG" />

### We didn't build an app. We built the missing infrastructure for an entire industry.

</div>

<br>

<div align="center">

| 🖥️ 6 Nodes | 👥 6 Engineers | ⏱️ 21+ Weeks | ☁️ 1 Private Cloud | 🧠 100% AI-Assisted |
|:---:|:---:|:---:|:---:|:---:|

</div>

---

## ⚡ The Spark

Tunisia has the beaches, the ruins, the medinas, the artisans, the food that ruins every other cuisine for you afterward.

What it didn't have: **one door to walk through to reach all of it.**

Bookings scattered across five apps. Drivers with no visibility. Artisans invisible to the world. So six engineering students at ESPRIT asked a different question — not *"can we build a booking app?"* but:

> **"Can we build the cloud infrastructure a whole tourism industry could run on — ourselves, from bare metal, in 21 weeks?"**

The answer is below. ⬇️

---

## 🧬 What Makes This Different

Everyone else digitized *a piece* of the trip. We digitized the *whole journey* — and gave it a brain.

<table>
<tr>
<td width="20%" align="center"><b>Booking.com</b></td>
<td width="20%" align="center"><b>Airbnb</b></td>
<td width="20%" align="center"><b>Expedia</b></td>
<td width="20%" align="center">⭐ <b>TunisiaTour</b></td>
</tr>
<tr><td colspan="4"><hr></td></tr>
<tr>
<td align="center">❌ Rooms only</td>
<td align="center">❌ Stays only</td>
<td align="center">🟡 Flights + hotels</td>
<td align="center">✅ Stays + rides + flights + events + artisans</td>
</tr>
<tr>
<td align="center">❌ No AI</td>
<td align="center">❌ No AI</td>
<td align="center">❌ No AI</td>
<td align="center">✅ AI negotiation agent + smart recommendations</td>
</tr>
<tr>
<td align="center">❌ No local craft</td>
<td align="center">❌ No local craft</td>
<td align="center">🟡 Barely</td>
<td align="center">✅ Full artisan marketplace</td>
</tr>
</table>

> *Others rent out rooms. We're rebuilding an economy's digital front door.*

---

## 🚀 The Build — From Bare Metal to Live App

Most student projects deploy to a free-tier server. **We built our own cloud first.**

<details>
<summary><b>☁️ Layer 1 — Private Cloud (click to expand)</b></summary>
<br>

```
$ openstack node list
  1 × Controller Node
  5 × Compute Nodes
  1 × Storage Node

$ openstack services --status
  ✔ Keystone   (Identity)
  ✔ Nova       (Compute)
  ✔ Neutron    (Networking — VXLAN, Floating IPs)
  ✔ Glance     (Images)
  ✔ Cinder     (Block Storage)
  ✔ Swift      (Object Storage)
  ✔ Heat       (Orchestration)
  ✔ Horizon    (Dashboard)
```
Full VM lifecycle wired by hand: **Keystone → Nova → Scheduler → Conductor → KVM.**
Multi-tenancy, self-healing, and infrastructure-as-code — before a single line of app code was written.

</details>

<details>
<summary><b>⚙️ Layer 2 — DevOps & Cloud-Native (click to expand)</b></summary>
<br>

```
$ ansible-playbook deploy.yml       # agentless automation over SSH
$ docker compose up                 # every service, containerized
$ kubectl get nodes
  master     Ready
  worker-1   Ready
  worker-2   Ready
$ helm install monitoring ./charts  # Prometheus + Grafana
```
Horizontally scalable. Highly available. Self-monitoring — with **AIOps anomaly detection** watching CPU spikes and pod failures before we do.

</details>

<details>
<summary><b>🎨 Layer 3 — The Application (click to expand)</b></summary>
<br>

Built on **Angular + Spring Boot + MySQL**, running live on the cloud above:

🏨 Stay booking with an **AI negotiation agent**
🚖 Rides with live GPS + multilingual real-time chat (STT/TTS)
✈️ Flights with comparison & e-tickets
🎭 Events with AI-curated recommendations + QR e-tickets
🛍️ Artisan marketplace with AI-generated product visuals
🤝 Community hub — voice messages, live location sharing
🔐 Face ID + 2FA security

</details>

---

## 🧰 Tech Arsenal

`Angular` `Spring Boot` `Java` `MySQL` `Postman` · `OpenStack` `Ansible` `Docker` `Kubernetes` `Helm` · `Prometheus` `Grafana` `AIOps`

---

## 🔗 Explore the Code

| Piece | Repo |
|---|---|
| 🌐 Frontend — Angular | **[abdelkader-belhaj/Angular1 →](https://github.com/abdelkader-belhaj/Angular1.git)** |
| ⚙️ Backend — Spring Boot | **[abdelkader-belhaj/springLooking →](https://github.com/abdelkader-belhaj/springLooking.git)** |

---

## 🌍 Why It Matters

Not just code — **jobs for drivers, visibility for artisans, income for interior regions, and a country's tourism industry pulled into the digital age.** Aligned with UN SDGs 8, 12, 5, and 10.

---

## 🧑‍🚀 Built By

**Rana Bchiri · Farah Boukesra · Abderrazek Chamekh · Rania Ben Ali · Abdelkader Belhaj · Zied Ben Khalifa**

<div align="center">

### 🇹🇳 *Together, let's restore Tunisia's tourism brilliance.*

</div>
