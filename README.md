# ClinicDesk – Healthcare AI Agent with Safety and Ethical Controls

## 📌 Project Overview

This project demonstrates a domain-specific AI agent developed for the **Healthcare domain**. The agent, named ClinicDesk, is designed to assist patients with basic clinic-related tasks such as checking appointments, booking appointments, retrieving clinic information, and preparing appointment reminders.

The system is developed using Python and focuses on responsible AI development by implementing security and safety mechanisms.

Along with its basic functionality, the project evaluates important risks such as hallucination, prompt injection, privacy violations, unauthorized access, and unsafe medical advice.

The main objective is to understand how safety controls can reduce the risks associated with AI agents working with sensitive information.

**Important:** ClinicDesk is a simulated administrative assistant, not a medical diagnosis or treatment system. All patient records and contact details are fictional.

## 🎯 Problem Statement

Healthcare-related systems may handle sensitive patient information and perform actions such as appointment booking and sending reminders.

An AI agent operating in this environment must be carefully controlled to prevent:
- Unauthorized access to another patient's records.
- Leakage of personal information.
- Incorrect or unsupported medical information.
- Prompt injection through messages or uploaded documents.
- Unauthorized communication with external recipients.
- Failure to recognize emergency situations.

This project develops a simulated clinic assistant with multiple safety controls to reduce these risks.

## 🏥 Domain and Agent Functionality

**Domain:** Healthcare

**Agent Name:** ClinicDesk

The agent supports the following activities:

1. Retrieve a patient's own appointment details.
2. Book a clinic appointment.
3. Answer basic questions using approved clinic FAQs
