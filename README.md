# SQL Forensics Case Study: The Murder of Roland Greene

## 📌 Project Overview
This repository contains a fictional SQL-based digital forensics investigation aimed at identifying the murderer of renowned art collector Roland Greene. The project demonstrates how structured data and SQL analysis can be used to reconstruct events, validate alibis, and reach evidence-based conclusions.

The focus is on analytical thinking, timeline reconstruction, and logical reasoning using relational datasets.

## 🧩 Case Summary

- Victim: Roland Greene
- Date: June 1, 2025
- Location: Vault Room, Private Estate
- Incident: Gunshot heard at exactly 8:00 PM
- Context: 30 guests were present at the estate

The investigation relies solely on digital evidence such as access logs, call records, motion sensors, and security system logs.

## 🗂️ Datasets Used

The following datasets were analyzed during the investigation:

- vault_access_logs
Records of individuals who accessed the Vault Room with timestamps.

- call_records
Phone call logs including caller, receiver, start time, and duration.

- motion_sensor_logs
Movement detection records in the vault hallway.

- security_logs
Logs indicating when the security feed was disabled.

- emergency_calls
Timestamped emergency call data following the incident.

## ⏱️ Reconstructed Timeline

A precise timeline was created by correlating all datasets:

- Time	     |  Event
7:55:45 PM	    Call between Roland Greene and Victor Hale
7:56:39 PM	    Call between Roland Greene and Susan Knight
7:56:35 PM	    Robin Ahmed accessed Vault Room
7:57 PM	        Victim last seen alive
8:00 PM	        Gunshot heard
8:00:55 PM	    Jamie Bennett accessed Vault Room
8:01:15 PM	    Motion detected in hallway
8:03 PM	        Security feed cut
8:04:53 PM	    Victor Shaw accessed Vault Room
8:05:45 PM	    Emergency call placed

## 🔍 Analysis Process

### 1. Access Log Filtering

Vault access logs were filtered to include only entries between 7:55 PM and 8:05 PM.

Result:

Only three individuals accessed the vault during the critical time window.

### 2. Alibi Verification Using Call Records

Call records were analyzed to determine whether suspects were actively on phone calls during the gunshot.

Result:
- Susan Knight was on an active call with the victim during the gunshot.
- Victor Hale was on a call shortly before the incident.

### 3. Motion Sensor Correlation

Motion sensor data was aligned with vault access times.

Result:
- Motion detection occurred shortly after Jamie Bennett’s vault entry, suggesting discovery rather than involvement.

### 4. Security System Interference Detection

Security logs were reviewed to identify abnormal behavior.

Result:
- The security feed was disabled after the gunshot.
- Victor Shaw accessed the vault after the feed was cut, indicating possible evidence tampering.
