﻿# Orapi_LLM_fire-tune

Documentation - Jérémy Indelicato 📃

Dans ce notebook, j'ai entrepris le fine-tuning d'un modèle de langage pour Orapi Maintenance, avec l'objectif de créer un système intelligent capable de comprendre et de recommander nos produits d'hygiène et de nettoyage spécialisés. Mon but était d'améliorer l'expérience utilisateur en fournissant des réponses précises et pertinentes aux questions concernant nos produits, réduisant ainsi la confusion face à la multitude de références disponibles. Pour y parvenir, j'ai commencé par préparer un dataset contenant les descriptions détaillées de nos produits, leurs avantages, et leur origine. Ce dataset est crucial car il permet au modèle de comprendre les caractéristiques spécifiques de chaque produit. Ensuite, j'ai converti ces descriptions textuelles en tokens à l'aide d'un tokenizer BERT, permettant ainsi au modèle de traiter et d'analyser les informations textuelles de manière efficace.

J'ai choisi d'utiliser un modèle BERT pré-entraîné, spécialement conçu pour les tâches de question-réponse, et je l'ai fine-tuné sur notre dataset pour qu'il s'adapte parfaitement à nos produits. Le processus d'entraînement s'est déroulé sur plusieurs époques, et j'ai évalué les performances du modèle pour m'assurer qu'il répondait correctement aux questions posées.J'ai testé le modèle en posant des questions spécifiques et en vérifiant la pertinence des réponses fournies. Cette étape m'a permis de valider la capacité du modèle à comprendre les descriptions des produits et à fournir des informations utiles aux utilisateurs.

L'ensemble de ce processus vise à créer un outil intelligent capable de guider les utilisateurs dans le choix des produits les mieux adaptés à leurs besoins. Ce projet illustre l'application pratique des modèles de langage dans le domaine du service client et de la recommandation de produits, et je suis convaincu qu'il apportera une réelle valeur ajoutée à notre entreprise.
