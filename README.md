---

# 🕸️ HartigBadge

**A mycelial approach to recognition.**
HartigBadge is an open source, web-based badge system for issuing, displaying, and verifying meaningful contributions within networked communities. Designed to interoperate with [Community Mycelium](https://github.com/ThaumazoOrg/CommunityMycelium), it serves as a lightweight, extensible platform for issuing **Open Badges** that mark trust, participation, and symbiotic growth.

> 🌿 *Inspired by the Hartig Net in mycorrhizal systems—where deep exchange between organisms takes place—HartigBadges are digital traces of connection, collaboration, and contribution.*

---

## ✨ Key Features

* 🔖 **Open Badge support** (IMS Global Open Badges 2.1 compliant)
* 🌐 **Web-based badge creation** and administration
* 🧩 **Interoperable with Community Mycelium** (users, groups, ACLs)
* 📄 Print-ready badge layout with proper rendering
* 🐍 Built with Python & Django for reliability and extensibility
* 🎨 Easy theming and template customization

---

## 🔧 Development Setup

### Prerequisites

* Python 3.x
* PostgreSQL
* Docker or Podman (recommended for development)
* Node.js + npm (for frontend build, if editing templates)

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/ThaumazoOrg/HartigBadge.git
   cd HartigBadge
   ```

2. **Create a virtual environment and install dependencies**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Set up environment variables**

   ```bash
   cp .env.example .env
   ```

   Update database and site config in `.env`.

4. **Run migrations and create an admin user**

   ```bash
   python manage.py migrate
   python manage.py createsuperuser
   ```

5. **Start the development server**

   ```bash
   python manage.py runserver
   ```

   Visit `http://localhost:8000` and log in with your admin credentials.

---

## 🧪 Default Admin Credentials (Dev Only)

* **Username**: `admin`
* **Password**: `admin`

*(Change these in production!)*

---

## 🧬 Project Origins & Evolution

HartigBadge is a fork of [LibreBadge](https://github.com/LibreBadge/LibreBadge), originally created as a fast, lightweight alternative to sluggish proprietary ID badge software like Datacard ID Centre and HID Asure ID.

This version has been refactored and reimagined by **Thaumazo** as part of the **Community Mycelium** project to align with decentralized, symbiotic, and recognition-based approaches to organizational structure and human collaboration.

---

## 🤝 Community & Contributions

We welcome contributions that align with the ethos of trust-building, decentralization, and open knowledge. Whether you're improving badge issuance, adding integrations, or just fixing a bug—your input is valued.

### To contribute:

1. Fork this repository
2. Create a feature branch (`git checkout -b feat/your-feature`)
3. Commit your changes
4. Submit a pull request

See [CODE\_OF\_CONDUCT.md](CODE_OF_CONDUCT.md) for community guidelines.

---

## 🧭 Related Projects

* [Community Mycelium](https://github.com/ThaumazoOrg/CommunityMycelium): user management, meetings, and access control
* [Hyphae](https://github.com/ThaumazoOrg/Hyphae): semantic linking and data interconnection layer (forthcoming)

---

## 📜 License

TBD — This fork may adopt an **AGPLv3** or **MIT license**, depending on community needs and integration plans. Stay tuned.

---

## 📚 Learning Resources

Want to contribute but new to Django? We recommend this excellent series by [@Sentdex](https://github.com/Sentdex):
🔗 [https://pythonprogramming.net/django-web-development-python-tutorial/](https://pythonprogramming.net/django-web-development-python-tutorial/)

---

## 💡 Why "HartigBadge"?

The **Hartig Net** is the living interface between fungi and plant roots—a woven, dynamic space of mutual benefit. In that spirit, a **HartigBadge** is a record of trust and shared growth—a trace of value exchanged at the living edge of community collaboration.

---

