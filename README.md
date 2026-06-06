# AWS Cloud Infrastructure — Project1
> Production-grade 3-tier web hosting architecture on Amazon Web Services

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
![Region](https://img.shields.io/badge/Region-ap--south--1-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)
![Services](https://img.shields.io/badge/AWS%20Services-17-blue?style=for-the-badge)

---

## What This Is

I built this project to understand how real cloud infrastructure works in production — not just how to click through the AWS console, but why each service exists and how everything connects together.

This came directly out of a previous failed attempt (TechNova project) where Auto Scaling kept replacing instances in a loop and I couldn't figure out why. I rebuilt the whole thing correctly, diagnosed the root cause, and documented every decision and failure along the way.

---

## Architecture

![Architecture Diagram](architecture-diagram.png)

**The traffic flow:**
