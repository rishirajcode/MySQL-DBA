# MySQL-DBA


A personal collection of MySQL Database Administration study materials, notes, interview preparation resources, cheatsheets, scripts, and references.  
Built for quick revision, interview prep (especially Vskills / certification-style questions), daily DBA tasks, and deepening understanding of MySQL internals.

**Repository**: [https://github.com/rishirajcode/MySQL-DBA](https://github.com/rishirajcode/MySQL-DBA)  
**Main content folder**: [`MYSQL RESOURCES`](./MYSQL%20RESOURCES)

## 🎯 Purpose

This repo serves as my centralized knowledge base for MySQL DBA topics, including:

- Core concepts (storage engines, transactions, locking, indexes)
- Backup & Recovery strategies
- Security best practices
- Performance tuning & query optimization
- Replication, high availability & scaling
- Error handling, logs & troubleshooting
- Interview questions & detailed answers (especially from popular sources like Vskills)
- Useful commands, configuration snippets, and quick-reference guides

Ideal for:

- MySQL DBA / Database Engineer interview preparation
- Certification study (Oracle MySQL, Vskills, etc.)
- Day-to-day administration reference
- Self-study and revision

## 📁 Repository Structure
MySQL-DBA/ <br> 
└── MYSQL RESOURCES/                  ← All actual content lives here <br>
├── Interview-Questions/          (if present – Vskills-style Q&A sets) <br>
├── Cheatsheets/                  (command references, syntax quick refs) <br>
├── Scripts/                      (backup, monitoring, tuning scripts) <br>
├── Notes/                        (concept explanations, diagrams if any)<br>
├── Configuration/                (my.cnf examples, InnoDB/Galera settings) <br>
├── Backup-Recovery/              (PITR, mysqldump, XtraBackup guides)<br>
├── Replication/                  (master-slave, Group Replication notes)<br>
└── ... (other topic-specific folders or files)<br>


> **Note**: Currently the repo is focused on the `MYSQL RESOURCES` directory. Feel free to explore subfolders for specific topics.
<br>
## 🔥 Key Highlights

- Comprehensive **interview Q&A** sets (100+ questions with detailed answers)
- Real-world DBA scenarios & best practices
- Performance tuning techniques (indexes, EXPLAIN, slow query log, etc.)
- Security hardening checklist
- Backup automation ideas & point-in-time recovery walkthroughs

## 🛠️ How to Use This Repository

1. **Browse online** — Just click through the folders on GitHub
2. **Clone locally** for offline reading/searching:
   ```bash
   git clone https://github.com/rishirajcode/MySQL-DBA.git
   cd MySQL-DBA/MYSQL\ RESOURCES

   📚 Main Topics Covered
<br>
Storage Engines (InnoDB vs MyISAM vs others) <br>
ACID, Transactions & Isolation Levels<br>
Indexing & Query Optimization (EXPLAIN, covering indexes, composite keys)<br>
Backup Strategies (logical vs physical, mysqldump, Percona XtraBackup)<br>
Point-in-Time Recovery (PITR) with binary logs<br>
Replication (async, semi-sync, Group Replication, Galera)<br>
High Availability & Scaling (sharding, read replicas, vertical vs horizontal)<br>
Security (privileges, encryption, audit plugin, SQL injection prevention)<br>
Monitoring & Troubleshooting (Performance Schema, slow log, error log)<br>
Error Handling & Deadlocks<br>
MySQL 8.0+ features (roles, window functions, CTEs in admin context)<br>

⚡ Quick Start – Most Viewed Files (based on common DBA needs)

Interview Questions compilation → start here for job prep
MySQL Performance Tuning Cheatsheet
Backup & Restore Best Practices
InnoDB Configuration Recommendations

🤝 Contributing
Contributions are welcome!<br>
You can:

Fix typos or improve explanations<br>
Add new interview questions + answers<br>
Contribute real-world config examples<br>
Add scripts (bash, Python, SQL) for common DBA tasks<br>
Include links to great external resources (with proper attribution)<br>

Just open an issue or pull request.
This repository is for personal/educational use.<br>
No formal license yet — consider everything MIT-licensed unless stated otherwise in individual files. Feel free to fork, learn from, and adapt — attribution appreciated.<br>
🙏 Acknowledgments 
<br>
Inspired by Vskills MySQL DBA interview questions & many community resources<br>
Thanks to MySQL documentation, Percona blogs, Severalnines, PlanetScale articles, and the open-source MySQL community<br>

Happy querying! 🐬<br>
Last updated: February 2025<br>
Maintained by: Rishi