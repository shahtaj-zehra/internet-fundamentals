# 🌐 How the Internet Works

This repository explains **how the internet works** and clearly demonstrates **what happens when a user types a URL in a web browser**.
It is written in **simple, interview-friendly language** for beginners, students, and aspiring developers.

---

## 🔗 What happens when I type a URL in the browser?

When a user types a URL like:

```
https://www.google.com/
```

The following steps happen **within milliseconds**:

---

## 1️⃣ URL Breakdown

The browser first understands the structure of the URL:

* **Protocol** → `https`
* **Domain name** → `google.com`
* **Path** → `/`

---

## 2️⃣ Cache Check

Before going to the internet, the browser checks:

* Browser cache
* Operating system cache
* DNS cache

✅ If the IP address is already stored, the **DNS lookup is skipped**, saving time.

---

## 3️⃣ DNS Lookup

DNS works like a **phone book of the internet**.
It converts a domain name into an IP address.

**Example:**

```
google.com → 142.250.190.14
```

---

## 4️⃣ Data Travels Through the Network

The request is broken into **small data packets** and travels through:

* WiFi / Mobile network
* ISP (Internet Service Provider)
* Routers and switches
* Fiber optic cables (including undersea cables)

📦 Each packet contains **source IP** and **destination IP**.

---

## 5️⃣ TCP Connection (3-Way Handshake)

A reliable connection is established using TCP:

* **SYN** → Client requests connection
* **SYN-ACK** → Server accepts request
* **ACK** → Client confirms

---

## 6️⃣ HTTPS Security (SSL / TLS)

If the website uses HTTPS:

* Data is encrypted
* Server identity is verified
* Communication becomes secure

🔒 This protects data from hackers and attackers.

---

## 7️⃣ HTTP Request

The browser sends an HTTP request to the server.

**Example:**

```
GET / HTTP/1.1
Host: google.com
```

---

## 8️⃣ Server Processing

The server:

* Receives the request
* Runs backend logic
* Fetches data from the database
* Prepares the response

---

## 9️⃣ HTTP Response

The server sends back:

* Status codes (200, 404, 500)
* HTML, CSS, JavaScript, images, or data

---

## 🔟 Browser Rendering

The browser:

* Reads HTML → creates DOM
* Applies CSS → creates CSSOM
* Executes JavaScript
* Displays the final webpage

🎉 The website appears on the screen.

---

## 🧠 Important Concepts

* DNS
* IP Address
* TCP vs UDP
* HTTP vs HTTPS
* SSL / TLS
* Proxy & Reverse Proxy
* VPN
* MAC Address

---

## 🎯 Short Interview Answer

> When a user types a URL, the browser resolves DNS to obtain the IP address, establishes a TCP connection, secures it using HTTPS, sends an HTTP request, receives a response from the server, and finally renders the webpage.


## 📷 Diagram

Below diagram shows the **complete internet workflow**:
<img width="1024" height="1536" alt="how internet works" src="https://github.com/user-attachments/assets/f3c9add7-bfe1-4885-902f-d88851a2ce28" />

