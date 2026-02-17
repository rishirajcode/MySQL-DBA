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
MySQL-DBA/
└── MYSQL RESOURCES/                  ← All actual content lives here
├── Interview-Questions/          (if present – Vskills-style Q&A sets)
├── Cheatsheets/                  (command references, syntax quick refs)
├── Scripts/                      (backup, monitoring, tuning scripts)
├── Notes/                        (concept explanations, diagrams if any)
├── Configuration/                (my.cnf examples, InnoDB/Galera settings)
├── Backup-Recovery/              (PITR, mysqldump, XtraBackup guides)
├── Replication/                  (master-slave, Group Replication notes)
└── ... (other topic-specific folders or files)


> **Note**: Currently the repo is focused on the `MYSQL RESOURCES` directory. Feel free to explore subfolders for specific topics.

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

Storage Engines (InnoDB vs MyISAM vs others)
ACID, Transactions & Isolation Levels
Indexing & Query Optimization (EXPLAIN, covering indexes, composite keys)
Backup Strategies (logical vs physical, mysqldump, Percona XtraBackup)
Point-in-Time Recovery (PITR) with binary logs
Replication (async, semi-sync, Group Replication, Galera)
High Availability & Scaling (sharding, read replicas, vertical vs horizontal)
Security (privileges, encryption, audit plugin, SQL injection prevention)
Monitoring & Troubleshooting (Performance Schema, slow log, error log)
Error Handling & Deadlocks
MySQL 8.0+ features (roles, window functions, CTEs in admin context)

⚡ Quick Start – Most Viewed Files (based on common DBA needs)

Interview Questions compilation → start here for job prep
MySQL Performance Tuning Cheatsheet
Backup & Restore Best Practices
InnoDB Configuration Recommendations

🤝 Contributing
Contributions are welcome!
You can:

Fix typos or improve explanations
Add new interview questions + answers
Contribute real-world config examples
Add scripts (bash, Python, SQL) for common DBA tasks
Include links to great external resources (with proper attribution)

Just open an issue or pull request.
📄 License
This repository is for personal/educational use.
No formal license yet — consider everything MIT-licensed unless stated otherwise in individual files. Feel free to fork, learn from, and adapt — attribution appreciated.
🙏 Acknowledgments

Inspired by Vskills MySQL DBA interview questions & many community resources
Thanks to MySQL documentation, Percona blogs, Severalnines, PlanetScale articles, and the open-source MySQL community

Happy querying! 🐬
Last updated: February 2025
Maintained by: Rishi