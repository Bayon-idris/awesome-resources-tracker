# Awesome Resources Tracker

## Flutter Resources  

### Tools and Tips  

#### Remove Loggers in Flutter Code  
Supprime rapidement les logs indésirables dans le code Flutter.  
✅ Prend en charge `print()`, `debugPrint()`, `logger.*()` et les modèles de logs personnalisés.  
✅ Nettoie le code pour une version prête en production en quelques secondes !  

- 🔗 [log_removal](https://pub.dev/packages/log_removal)  
  Cet outil supprime automatiquement tous les `print`, `debugPrint` et autres loggers dans une application Flutter.  


#### Remove Unused Imports  
Supprime automatiquement tous les imports non utilisés dans un projet Flutter.  

```bash
dart fix --apply --code=unused_import
```


#### Showcase & Discovery  
Outils permettant d'afficher des guides interactifs dans une application Flutter :  

- 🔗 [Feature Discovery](https://pub.dev/packages/feature_discovery)  
- 🔗 [Showcase View](https://pub.dev/packages/showcaseview)  


### Optimization Tools  

#### Analyse des Assets Non Utilisés  
Un outil permettant d’analyser un projet et de détecter les assets inutilisés afin d’optimiser la taille de l’application.  
- 🔗 [unused_assets_cli](https://github.com/loicgeek/unused_assets_cli)  

---

### Project Setup  

#### Flutter Kit  
Un projet préconfiguré avec des configurations de routes et autres paramètres essentiels pour démarrer rapidement.  
- 🔗 [flutter_kit](https://github.com/stevenosse/flutter_kit)  
```
