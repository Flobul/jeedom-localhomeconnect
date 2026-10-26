# Local Home Connect pour Jeedom

[![Licence](https://img.shields.io/badge/Licence-GPL--3.0-blue?style=flat-square)](https://github.com/Flobul/jeedom-localhomeconnect/blob/HEAD/LICENSE)
[![Langage](https://img.shields.io/badge/Langage-PHP-informational?style=flat-square)](https://github.com/Flobul/jeedom-localhomeconnect)
[![Dernière mise à jour](https://img.shields.io/badge/Derniere_mise_a_jour-04/10/2026-brightgreen?style=flat-square)](https://github.com/Flobul/jeedom-localhomeconnect/commits)
[![Tickets ouverts](https://img.shields.io/badge/Tickets_ouverts-0-brightgreen?style=flat-square)](https://github.com/Flobul/jeedom-localhomeconnect/issues)
[![Demandes de fusion ouvertes](https://img.shields.io/badge/Demandes_de_fusion_ouvertes-0-brightgreen?style=flat-square)](https://github.com/Flobul/jeedom-localhomeconnect/pulls)

<!-- market-badges:start -->
[![Note](https://img.shields.io/badge/Note-Aucun%20avis-lightgrey?style=flat-square)](https://market.jeedom.com/index.php?v=d&p=market_display&id=4696)
[![Prix](https://img.shields.io/badge/Prix-Gratuit-brightgreen?style=flat-square)](https://market.jeedom.com/index.php?v=d&p=market_display&id=4696)
[![Installations](https://img.shields.io/badge/Installations-13-blueviolet?style=flat-square)](https://market.jeedom.com/index.php?v=d&p=market_display&id=4696)
<!-- market-badges:end -->

Retrouvez vos appareils Bosch, Siemens et autres marques du groupe BSH compatibles Home Connect dans Jeedom : four, lave-vaisselle, lave-linge, table de cuisson…

Suivez leur état, recevez leurs mises à jour en temps réel et utilisez les commandes disponibles selon le modèle. Après la configuration initiale, Jeedom communique directement avec vos appareils sur votre réseau local, sans passer par le cloud Home Connect.

## Avant de commencer

- Jeedom 4.4 ou plus récent, sous Debian 12.
- Des appareils déjà associés à l’application Home Connect.
- Vos identifiants SingleKey, utilisés pour vous connecter à Home Connect.
- Jeedom et les appareils connectés au même réseau local.

## Démarrage rapide

1. Installez le plugin et ses **dépendances** depuis Jeedom.
2. Dans la configuration du plugin, renseignez vos identifiants SingleKey et enregistrez.
3. Cliquez sur **Récupérer automatiquement** pour ajouter vos appareils. Si une connexion dans le navigateur est demandée, suivez les instructions affichées.
4. Démarrez le **démon**, le service qui assure la communication avec vos appareils.
5. Sur la page des équipements, cliquez sur **Découvrir** pour les retrouver sur votre réseau.

Pour les étapes détaillées ou les autres méthodes d’ajout, consultez la [documentation complète](docs/fr_FR/index.md).

## Au quotidien

Les états se mettent à jour automatiquement. Les commandes proposées dépendent de chaque appareil et de ses fonctions disponibles. Le démarrage à distance peut nécessiter une autorisation sur l’appareil lui-même.

En cas de difficulté, ouvrez **Santé** pour vérifier les connexions et utilisez **Tester la communication** sur l’appareil concerné. Le plugin corrige automatiquement les permissions de son stockage privé lorsque cela est possible.

## Besoin d’aide ?

- [Documentation et dépannage](docs/fr_FR/index.md)
- [Historique des versions](docs/CHANGELOG.md)
- [Communauté Jeedom](https://community.jeedom.com/tag/plugin-localhomeconnect)

## Documentation

La documentation détaillée est disponible dans [docs/fr_FR/index.md](docs/fr_FR/index.md).

## Sécurité

Consultez la [politique de sécurité](SECURITY.md) avant de transmettre un rapport ou des journaux. Ne publiez jamais de secret, de jeton ou de mot de passe dans une issue publique.

## Licence

Ce projet est distribué sous licence **GPL-3.0**. Consultez le fichier [LICENSE](LICENSE) pour le texte complet.

---

<p align="center">
  <a href="https://github.com/sponsors/Flobul">
    <img src="https://img.shields.io/badge/Sponsoriser%20ce%20projet-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors" alt="Sponsoriser ce projet sur GitHub">
  </a>
</p>
