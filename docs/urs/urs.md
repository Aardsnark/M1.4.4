
### User Requirements Specification Document
##### ITS ICT - Gruppo di Lavoro X


**VERSION : 0.1**

**Authors**  
Federico Zunino
Serena Schincaglia
Simone Schiano

**REVISION HISTORY**

| Version    | Date        | Authors      | Notes        |
| ----------- | ----------- | ----------- | ----------- |
| 0.1 | 15/09/2022 | | Nuove funzionalità e profili verranno aggiunti nelle prossime versioni.  |


# Table of Contents

1. [Introduction](#p1)
	1. [Document Scope](#sp1.1)
	2. [Definitios and Acronym](#sp1.2) 
	3. [References](#sp1.3)
2. [System Description](#p2)
	1. [Context and Motivation](#sp2.1)
	2. [Project Objectives](#sp2.2)
3. [Requirement](#p3)
 	1. [Stakeholders](#sp3.1)
 	2. [Functional Requirements](#sp3.2)
 	3. [Non-Functional Requirements](#sp3.3)
  
  

<a name="p1"></a>

## 1. Introduction

<a name="sp1.1"></a>

### 1.1 Document Scope

Questo documento va ad illustrare gli update e i requisiti del progetto "Sistema Registrazione Esami" realizzato per la Online University UniSkaven.

<a name="sp1.2"></a>

### 1.2 Definitios and Acronym


| Acronym				| Definition | 
| ------------------------------------- | ----------- | 
| XXXX                                  | XXXX |

<a name="sp1.3"></a>

### 1.3 References 

<a name="p2"></a>

## 2. System Description
<a name="sp2.15"></a>

### 2.1 Context and Motivation

Dopo aver esaminato l'offerta di software dedicati alla creazione e gestioni di corsi ed esami universitari, Uni-Skaven ha deciso di commissionare la realizzazione di un software proprietario che offrisse opzioni di scalability per il suo numero sempre crescente di studenti e personale, nonchè il futuro ampliamento della loro offerta formativa.

<a name="sp2.2"></a>

### 2.2 Project Obectives 

Il software prevede di poter creare profili unici per ogni studente e docente iscritto ad Uni-Skaven. L'amministrazione di UNI-Skaven creerà ed aggiungerà i corsi all'interno dei percorsi di laurea con i quasi si interfacceranno sia i docenti che gli studenti tramite browser o app dedicata. 

I docenti di Uni-Skaven potranno creare nuovi esami per i corsi da loro insegnati, interagire con la lista degli iscritti a ciascun esame e assegnare votazioni agli studenti che hanno sostenuto e passato l'esame.

Gli studenti Uni-Skaven potranno iscriversi e disiscriversi ai corsi, agli esami disponibili per ogni corso che non hanno già passato, e consultare la propria lista dei voti degli esami passati. 

<a name="p3"></a>

## 3. Requirements

| Priorità | Significato | 
| --------------- | ----------- | 
| M | **Mandatory:**   |
| D | **Desiderable:** |
| O | **Optional:**    |
| E | **future Enhancement:** |

<a name="sp3.1"></a>
### 3.1 Stakeholders

| Gruppo | Ruoli |
| ----------- | ----------- | 
|Personale Amministrativo Uni-Skaven| Presidente Uni-Skaven, Direttori Dipartimenti, Responsabile Web, Personale Segreteria |
| ----------- | ----------- | 
|Personale Scolastico Uni-Skaven| Docenti, Studenti |

<a name="sp3.2"></a>
### 3.2 Functional Requirements 

| ID | Descrizione | Priorità |
| --------------- | ----------- | ---------- | 
| 1.0 |  L'amministrazione crea profili docenti |M|
| --------------- | ----------- | ---------- | 
| 2.0 |  L'amministrazione crea profili studenti |M|
| --------------- | ----------- | ---------- | 
| 3.0 |  L'amministrazione crea corsi per ogni percorso di laurea |M|
| --------------- | ----------- | ---------- | 
| 4.0 |  L'amministrazione assegna i docenti ai corsi |M|

<a name="sp3.3"></a>
### 3.3 Non-Functional Requirements 
 
| ID | Descrizione | Priorità |
| --------------- | ----------- | ---------- | 
| 1.0 | Il software deve essere compatibile con Windows, MACOS, e Linux |M|
| --------------- | ----------- | ---------- | 
| 2.0 | Il software deve essere accessibile tramite browser |M|
| --------------- | ----------- | ---------- | 
| 3.0 | Il software deve essere accessibile tramite app |M|
| --------------- | ----------- | ---------- | 
| 4.0 | Il software deve rispettare i dettami del GDPR |M|
