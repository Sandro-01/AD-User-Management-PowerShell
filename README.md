# 🏢 PowerShell Active Directory User Manager

> **Tool interattivo per l'automazione della gestione utenti Active Directory**

[![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-blue?logo=powershell)](https://docs.microsoft.com/en-us/powershell/)
[![Active Directory](https://img.shields.io/badge/Active%20Directory-RSAT-green)](https://docs.microsoft.com/en-us/troubleshoot/windows-server/system-management-components/remote-server-administration-tools)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🎯 Panoramica del Progetto

Script PowerShell professionale sviluppato per automatizzare le operazioni più comuni di gestione utenti in ambienti Active Directory. Progettato per SysAdmin e tecnici IT che necessitano di strumenti efficienti per la gestione quotidiana degli utenti.

## ✨ Caratteristiche Principali

- **🔄 Creazione massiva utenti**: Import da file CSV con assegnazione automatica OU e gruppi
- **🔐 Gestione password**: Reset con notifiche email simulate
- **🔍 Ricerca avanzata**: Trova utenti per nome, cognome o username
- **⚠️ Gestione account**: Disabilitazione e spostamento in OU dedicate
- **📝 Sistema di logging**: Tracciamento completo delle operazioni
- **🎨 Interfaccia colorata**: Menu CLI intuitivo e user-friendly
- **📋 Template automatici**: Generazione file CSV di esempio

## 📋 Requisiti di Sistema

- **Sistema Operativo**: Windows Server 2016+ o Windows 10/11 con RSAT
- **PowerShell**: Versione 5.1 o superiore
- **Moduli**: ActiveDirectory (incluso in RSAT)
- **Permessi**: Privilegi amministrativi su Active Directory
- **Rete**: Connessione al Domain Controller

## 🚀 Installazione e Configurazione

### 1. Clona il repository
```powershell
git clone https://github.com/Sandro-01/AD-User-Management-PowerShell.git
cd AD-User-Management-PowerShell
