<div style="display: flex; align-items: center; justify-content: space-between;">
  <h1>📚 Gestion de bases de données (BDD)</h1>
  <img src="Img/switchtoopen1.png" alt="Description de l'image" width="150" height="150">
</div>

---

## Sommaire 📖 <a id="sommaire"></a>
1. [📂 Systèmes de gestion de bases de données relationnelles (SGBDR)](#sgbdr)
2. [🛠️ Outils d'administration de bases de données](#outils-administration)
3. [📇 Bases de données NoSQL](#bases-nosql)
4. [🌐 Bases de données orientées graphes](#bases-graphes)
5. [🗃️ Bases de données orientées colonnes](#bases-colonnes)
6. [⚙️ Bases de données orientées objets](#bases-objets)
7. [🔍 Bases de données pour le traitement analytique (OLAP)](#bases-olap)
8. [💾 Bases de données en mémoire](#bases-memoire)
9. [☁️ Solutions de clustering et haute disponibilité](#solutions-clustering)

---

## 📂 Systèmes de gestion de bases de données relationnelles (SGBDR) <a id="sgbdr"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[MySQL Community](https://www.mysql.com/)** | GPLv2	 | Populaire pour les applications web | SGBDR open source [En savoir plus](https://www.mysql.com/) | <div align="center"><a href="https://www.mysql.com/">🔗</a></div> |
| **[PostgreSQL](https://www.postgresql.org/)** | PostgreSQL License (=MIT) | Haute disponibilité, conformité ACID | SGBDR avancé [En savoir plus](https://www.postgresql.org/) | <div align="center"><a href="https://www.postgresql.org/">🔗</a></div> |
| **[MariaDB](https://mariadb.org/)** | GPLv2 + exception FLOSS | Fonctionnalités avancées, optimisations | Fork de MySQL [En savoir plus](https://mariadb.org/) | <div align="center"><a href="https://mariadb.org/">🔗</a></div> |
| **[SQLite](https://www.sqlite.org/)** | Domaine public (ou CC0) | Légère, sans serveur | Base de données relationnelle [En savoir plus](https://www.sqlite.org/) | <div align="center"><a href="https://www.sqlite.org/">🔗</a></div> | 

[🔝 Retour au sommaire](#sommaire)

---

## 🛠️ Outils d'administration de bases de données <a id="outils-administration"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[pgAdmin](https://www.pgadmin.org/)** | PostgreSQL Licence (OSI) | Interface graphique pour PostgreSQL | Administration avancée de PostgreSQL, web et desktop | <div align="center"><a href="https://www.pgadmin.org/">🔗</a></div> |
| **[DBeaver](https://dbeaver.io/)** | Apache License 2.0 | Multi-plateforme, multi-SGBD | Gestion de nombreuses bases (MySQL, PostgreSQL, SQLite, etc.) | <div align="center"><a href="https://dbeaver.io/">🔗</a></div> |
| **[Adminer](https://www.adminer.org/)** | Apache License 2.0 | Interface légère pour la gestion de BDD | Alternative à phpMyAdmin, mono-fichier PHP, multi-SGBD | <div align="center"><a href="https://www.adminer.org/">🔗</a></div> |
| **[HeidiSQL](https://www.heidisql.com/)** | GPLv2 | Interface simple, fonctions avancées | Gestion de BDD MySQL, MariaDB, PostgreSQL, SQL Server, SQLite | <div align="center"><a href="https://www.heidisql.com/">🔗</a></div> |
| **[Beekeeper Studio](https://www.beekeeperstudio.io/)** | GPLv3 | Interface moderne, conviviale | Gestion SQL multi-bases, desktop moderne, Community Edition | <div align="center"><a href="https://www.beekeeperstudio.io/">🔗</a></div> |
| **[phpMyAdmin](https://www.phpmyadmin.net/)** | GPLv2 | Fonctionnalités complètes pour administration | Gestion de BDD MySQL, MariaDB, web, très répandu | <div align="center"><a href="https://www.phpmyadmin.net/">🔗</a></div> |
| **[SQuirreL SQL](http://squirrel-sql.sourceforge.net/)** | GPLv2 | Client SQL compatible multis-SGBD | Pour utilisateurs avancés, support JDBC, multiplateforme | <div align="center"><a href="http://squirrel-sql.sourceforge.net/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📇 Bases de données NoSQL <a id="bases-nosql"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[MongoDB < 2018](https://www.mongodb.com/)** | AGPLv3 | Bases de données orientées documents | base de données NoSQL orientée documents, très populaire pour le développement d’applications modernes. Elle stocke les données sous forme de documents JSON (BSON), ce qui la rend flexible et adaptée à des données non structurées ou évolutives | <div align="center"><a href="https://www.mongodb.com/">🔗</a></div> |
| **[Apache CouchDB](https://couchdb.apache.org/)** | Apache License 2.0 | Stockage JSON, API REST | Apache CouchDB est une base de données NoSQL orientée documents, développée par la fondation Apache. Elle stocke les données sous forme de documents JSON, accessibles et manipulables via une API HTTP RESTful, ce qui la rend particulièrement adaptée aux applications web et mobiles | <div align="center"><a href="https://couchdb.apache.org/">🔗</a></div> |
| **[Apache Cassandra](http://cassandra.apache.org/)** | Apache License 2.0 | Scalabilité et haute disponibilité | Apache Cassandra est une base de données NoSQL distribuée, conçue pour gérer de très grandes quantités de données réparties sur plusieurs serveurs (nœuds) avec une haute disponibilité et sans point de défaillance unique. | <div align="center"><a href="http://cassandra.apache.org/">🔗</a></div> |
| **[Redis](https://redis.io/)** | BSD 3-Clause	 | Gestion clés-valeurs | Redis est une base de données NoSQL en mémoire, très rapide, utilisée principalement comme cache, broker de messages et magasin clé-valeur. Elle est particulièrement appréciée pour ses performances exceptionnelles, sa simplicité d’utilisation et sa polyvalence | <div align="center"><a href="https://redis.io/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🌐 Bases de données orientées graphes <a id="bases-graphes"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[Neo4j](https://neo4j.com/)** | GPLv3 (Community), Commerciale | Prise en charge des graphes | Neo4j est une base de données orientée graphes native, qui stocke les données sous forme de nœuds et relations, optimisée pour des requêtes rapides sur des données très connectées. Elle est largement utilisée pour la modélisation de réseaux complexes, la détection de fraudes, et les graphes de connaissances | <div align="center"><a href="https://neo4j.com/">🔗</a></div> |
| **[ArangoDB](https://www.arangodb.com/)** | Apache License 2.0 | Base de données multi-modèles | ArangoDB est une base de données multi-modèles open source combinant documents, graphes et clés-valeurs dans un seul moteur, offrant ainsi une grande flexibilité pour gérer différents types de données. Elle permet de réaliser des requêtes complexes sur des graphes tout en supportant les fonctionnalités classiques des bases documentaires | <div align="center"><a href="https://www.arangodb.com/">🔗</a></div> |
| **[JanusGraph](https://janusgraph.org/)** | Apache License 2.0 | Graphes distribués et scalables | JanusGraph est une base de données orientée graphes distribuée, conçue pour gérer de très grands graphes à l’échelle, avec un support pour la scalabilité horizontale et la tolérance aux pannes. Elle s’appuie sur des systèmes de stockage et d’indexation externes comme Apache Cassandra ou HBase pour la persistance | <div align="center"><a href="https://janusgraph.org/">🔗</a></div> |
| **[OrientDB Community](https://orientdb.org/)** | Apache License 2.0 | Multi-modèles avec support des graphes | OrientDB est une base de données multi-modèles qui combine les fonctionnalités de base de données documentaire et orientée graphes, permettant de stocker et interroger des données complexes dans un même système. Elle offre une interface SQL étendue pour manipuler les graphes et les documents, facilitant la transition depuis les bases relationnelles | <div align="center"><a href="https://orientdb.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🗃️ Bases de données orientées colonnes <a id="bases-colonnes"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[Apache HBase](https://hbase.apache.org/)** | Apache License 2.0	 | Adaptée aux grandes données | Base de données NoSQL distribuée, open source, conçue pour stocker et gérer des milliards de lignes et de colonnes sur des clusters Hadoop. Elle offre une forte intégration avec l’écosystème Hadoop, une scalabilité linéaire et une consistance stricte pour les lectures et écritures | <div align="center"><a href="https://hbase.apache.org/">🔗</a></div> |
| **[ScyllaDB](https://www.scylladb.com/)** | AGPLv3 | Performance élevée | Base de données NoSQL open source, compatible Cassandra, réécrite en C++ pour offrir des performances très élevées, une faible latence et une scalabilité horizontale optimale. Elle se distingue par son architecture optimisée pour le matériel moderne et sa capacité à traiter des charges massives en temps réel | <div align="center"><a href="https://www.scylladb.com/">🔗</a></div> |
| **[Hypertable](http://hypertable.org/)** | GPLv2	 | Inspirée de Google Bigtable | Base de données orientée colonnes open source, inspirée de Google Bigtable, conçue pour gérer de très grands volumes de données structurées sur des clusters. Elle vise à offrir une alternative performante et efficace à HBase, avec une architecture similaire pour les applications Big Data | <div align="center"><a href="http://hypertable.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## ⚙️ Bases de données orientées objets <a id="bases-objets"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[db4o](https://db4o.sourceforge.net/)** | GPLv2	 | Applications embarquées | db4o est une base de données orientée objets, légère et embarquée, conçue pour Java et .NET, permettant de stocker directement les objets de l’application sans transformation ni mapping. Elle s’intègre facilement comme bibliothèque dans les applications, sans installation séparée, et propose une API simple pour la persistance native et la requête d’objets. | <div align="center"><a href="https://db4o.sourceforge.net/">🔗</a></div> |
| **[ObjectBox](https://objectbox.io/)** | Apache License 2.0	 | Appareils mobiles et IoT | ObjectBox est une base de données orientée objets ultra-rapide, optimisée pour les appareils mobiles et l’IoT, avec synchronisation intégrée et une API moderne. Elle vise la performance et la simplicité d’usage, tout en offrant une licence open source permissive (Apache 2.0) | <div align="center"><a href="https://objectbox.io/">🔗</a></div> |
| **[Perst](http://www.mcobject.com/perst)** | GPLv2	 | Embarquée en Java et C# | Perst est une base de données orientée objets embarquée, écrite en Java et C#, adaptée aux applications mobiles et systèmes embarqués. Elle se distingue par sa légèreté, sa rapidité et sa capacité à fonctionner dans des environnements à ressources limitées | <div align="center"><a href="http://www.mcobject.com/perst">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔍 Bases de données pour le traitement analytique (OLAP) <a id="bases-olap"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[ClickHouse](https://clickhouse.com/)** | Apache License 2.0	 | Traitement analytique en temps réel | ClickHouse est une base de données open source orientée colonnes, conçue pour le traitement analytique en temps réel sur de très grands volumes de données. Elle offre des performances exceptionnelles grâce à son stockage en colonnes, sa compression avancée et son moteur d’exécution vectorisé | <div align="center"><a href="https://clickhouse.com/">🔗</a></div> |
| **[Apache Druid](https://druid.apache.org/)** | Apache License 2.0	 | Requêtes analytiques en temps réel | Apache Druid est une base de données OLAP distribuée, spécialisée dans l’analyse en temps réel de flux de données et la création de tableaux de bord interactifs. Elle combine ingestion native en streaming, indexation automatique et architecture modulaire pour offrir des requêtes analytiques à très faible latence | <div align="center"><a href="https://druid.apache.org/">🔗</a></div> |
| **[MonetDB](https://www.monetdb.org/)** | MPL 2.0 (Mozilla Public License 2.0) | Requêtes analytiques rapides | MonetDB est une base de données open source orientée colonnes, optimisée pour les requêtes analytiques complexes et le traitement de gros volumes de données. Elle utilise un moteur vectoriel et le stockage en colonnes pour accélérer les opérations OLAP et la business intelligence, tout en restant flexible pour divers cas d’usage analytiques. | <div align="center"><a href="https://www.monetdb.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 💾 Bases de données en mémoire <a id="bases-memoire"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[Redis](https://redis.io/)** | BSD 3-Clause	 | Gestion clés-valeurs | Redis est une base de données NoSQL en mémoire, très rapide, utilisée principalement comme cache, broker de messages et magasin clé-valeur. Elle est particulièrement appréciée pour ses performances exceptionnelles, sa simplicité d’utilisation et sa polyvalence | <div align="center"><a href="https://redis.io/">🔗</a></div> |
| **[Memcached](https://memcached.org/)** | BSD 3-Clause	 | Mémoire cache distribué | Memcached est un système de cache distribué en mémoire, open source, qui stocke des paires clé-valeur pour accélérer l’accès aux données et réduire la charge sur les bases de données. Il offre des temps de réponse inférieurs à la milliseconde, une architecture multithread et une excellente évolutivité pour les applications web à fort trafic | <div align="center"><a href="https://memcached.org/">🔗</a></div> |
| **[VoltDB Community](https://www.voltdb.com/)** | AGPL v3 (Community Edition) | Haute vitesse | VoltDB est une base de données relationnelle en mémoire, conçue pour les traitements transactionnels ultra-rapides et le traitement de gros volumes de données en temps réel. Elle combine la persistance ACID, la scalabilité horizontale et une faible latence, ce qui la rend idéale pour les applications critiques nécessitant des réponses instantanées | <div align="center"><a href="https://www.voltdb.com/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## ☁️ Solutions de clustering et haute disponibilité <a id="solutions-clustering"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **[Patroni](https://github.com/zalando/patroni)** | MIT | Clustering pour PostgreSQL | Patroni est une solution mature et très utilisée pour la haute disponibilité PostgreSQL, sous licence MIT, garantissant automatisation du failover et gestion du cluster via un store distribué (etcd, Consul, ZooKeeper). | <div align="center"><a href="https://github.com/zalando/patroni">🔗</a></div> |
| **[Galera Cluster](https://galeracluster.com/)** | GPLv2 | Réplication multi-master | Galera Cluster fournit une réplication synchrone multi-maître robuste pour MariaDB/MySQL, sous GPLv2, assurant cohérence forte et tolérance aux pannes. | <div align="center"><a href="https://galeracluster.com/">🔗</a></div> |
| **[PostgreSQL BDR](https://2ndquadrant.com/en/resources/bdr/)** | PostgreSQL License (=BSD) | Réplication multi-master | PostgreSQL BDR est une extension PostgreSQL sous licence PostgreSQL License (similaire à BSD), permettant une réplication multi-maître asynchrone adaptée aux déploiements distribués. | <div align="center"><a href="https://2ndquadrant.com/en/resources/bdr/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---
