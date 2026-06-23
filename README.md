# AI-Engineering-Challenge: Pretty-Good-AI Voice Bot

## Goal
Build an automated Python voice bot that:
- Places outbound calls to Pretty Good AI's test line
- Holds natural patient conversations with the AI agent
- Records and transcribes both sides of the conversation
- Surfaces bugs and quality issues in the agent's responses

---

## Ambiguities & Assumptions

Working without specifications from subject matter experts, customer support, or technical team members, I made the following assumptions and documented my reasoning:

### 1. Orthopedic Office Services

**Question:** What specific services does the orthopedic office provide?

**Criteria for Determination:**
- Is it an independent practice, group practice, walk-in clinic, or hospital-based facility?
- What are their core subspecialties (sports medicine, orthopedic trauma, spine surgery, hip & knee / joint replacement, etc.)?

**Assumption Made:**
Based on the call to the test line, confirmation text upon sign-up, and research on types of orthopedic doctors, I assumed this is an office providing **general orthopedic services** rather than a specialty location.

### 2. Technology Stack

**Question:** What technology stack should be used?

**Criteria for Determination:**
- Operating System: Microsoft Windows 11 Pro
- Processor: 11th Gen Intel Core i5-11600K @ 3.90GHz (6 cores, 12 logical processors)
- RAM: 32.0 GB

**Decision Process:**
Without prior experience and no senior developer to work with, I:
1. Conducted research via Google and Claude on how to develop this solution
2. In Progress: validating findings by viewing YouTube "how-to" videos
3. Documented the complete research and design rationale in a separate document: *Research & Design Rationale*

### 3. Work Reporting Format

**Question:** How should progress be reported—daily, weekly, or upon project completion?

**Assumption Made:**
Drawing on experience working under minimal supervision, I will be maintaining a **daily log similar to JIRA comments** for comprehensive progress tracking during the development of this portfolio project.

### 4. Documentation Format

**Question:** What format should documentation follow?

**Assumption Made:**
No specifications were provided. Documentation follows standard software engineering conventions with clear hierarchies, versioning, and technical clarity.

---

## Project Structure

- **Main Application:** Python voice bot implementation
- **Research & Design Rationale:** Complete decision-making and technology selection process
- **Daily Development Log:** Progress tracking and issue documentation
