# Welcome to RebornX CMS

**A modernized fork of XOOPS 2.0.5**  
RebornX brings the classic XOOPS codebase into the modern era with PHP 8.2+ compatibility, modern database drivers, a new theming system, true internationalization (i18n), and enhanced security — while preserving the modular architecture that made XOOPS popular.

---

## 🚀 Key Features

| Category | Highlights |
|----------|------------|
| **Core Modernization** | PHP 8.2+, MySQLi/PDO, exception-based error handling |
| **Theming** | Smarty templating, template inheritance, responsive by default |
| **i18n & l10n** | Full UTF-8, locale handling, pluralization, multi-language content |
| **Database** | Prepared statements, SQL injection protection, migration tools |
| **Security** | bcrypt/argon2 passwords, CSRF tokens, XSS prevention, secure sessions |
| **Pre‑packaged Modules** | News, NewBB forum, Downloads, Links, FAQ, Polls, Members, Partners, Contact, Sections, Headlines |

---

## 📦 Included Modules

- Contact – Customizable contact forms  
- myDownloads – File/software download manager  
- myLinks – Web link directory  
- NewBB – Discussion forum with PM  
- News – Article publishing with workflow  
- Sections – Hierarchical content  
- System – Core admin & user management  
- XoopsFAQ – FAQ manager  
- XoopsHeadline – RSS feed aggregator  
- XoopsMembers – Member directory  
- XoopsPartners – Partner/affiliate links  
- XoopsPoll – Polls & surveys  

---

## 🔧 Requirements

- **Web server:** Apache 2.4+ (mod_rewrite) or Nginx  
- **PHP:** 8.2 or higher  
- **Database:** MySQL 5.7+ / MariaDB 10.3+  
- **Extensions:** `mbstring`, `gd`/`imagick`, `json`, `session`, `filter`, `ctype`, `tokenizer`  

---

## 📥 Quick Installation

1. Download the latest release from [our Releases page](https://github.com/RebornX-CMS/rebornx-core/releases)  
2. Extract to your web root (e.g., `/var/www/html/rebornx`)  
3. Create a database and user  
4. Copy `mainfile.dist.php` to `mainfile.php` and edit credentials  
5. Visit `/install/` and follow the installer  
6. Remove the `install/` directory after completion  

For detailed instructions, see the [Core Repository README](https://github.com/RebornX-CMS/rebornx-core).

---

## 🔄 Upgrading from XOOPS 2.0.x

1. Back up your database and files  
2. Replace all files with RebornX (keep `mainfile.php` and `uploads/`)  
3. Run `/upgrade/` script  
4. Review admin panel for any adjustments  

---

## 🧩 Repository Structure

- **[rebornx-core](https://github.com/RebornX-CMS/rebornx-core)** – Main CMS codebase  
- **[rebornx-modules](https://github.com/RebornX-CMS/rebornx-modules)** – Additional / community modules  
- **[rebornx-themes](https://github.com/RebornX-CMS/rebornx-themes)** – Theme repository  
- **[rebornx-docs](https://github.com/RebornX-CMS/rebornx-docs)** – Documentation & wiki  

---

## 🤝 Contributing

We welcome contributions! Please follow our guidelines:

- Fork the repository you want to contribute to  
- Create a feature branch: `git checkout -b feature/your-feature`  
- Follow **PSR-12** coding standards  
- Write PHPDoc for public methods  
- Use prepared statements for database queries  
- Escape all output with `htmlspecialchars()` or our sanitizers  

Submit a pull request to the relevant repository.

---

## 📄 License

**RebornX CMS** is released under the **GNU General Public License v3.0 (GPLv3)**.  
See the [LICENSE](https://github.com/RebornX-CMS/rebornx-core/blob/main/LICENSE) file for the full text.

> Based on XOOPS 2.0.5 (2000–2003 XOOPS.org) – also under GPL.

---

## 🌍 Community & Support

- [GitHub Discussions](https://github.com/orgs/RebornX-CMS/discussions)  
- [Documentation](https://github.com/RebornX-CMS/rebornx-docs)  
- [Issue Tracker](https://github.com/RebornX-CMS/rebornx-core/issues)  

---

*Maintained by the RebornX CMS project contributors – bringing XOOPS back to life.*# .github
