# Database Management Using an AI Agent with n8n and RDS

## Roles

- Cloud Developer
- Machine Learning Engineer
- AI Engineer

## Categories

- Compute
- Machine Learning

---

# Lab Details

1. In this lab, you will create a **serverless AI-powered database management agent** using **n8n hosted on an AWS EC2 instance**, integrated with **Amazon Bedrock using the Nova Lite model** and an **Amazon RDS PostgreSQL database**.

   The workflow uses n8n nodes to:

   - Trigger on chat messages
   - Process queries using Amazon Bedrock
   - Execute SQL queries on Amazon RDS
   - Maintain conversation memory
   - Provide a frontend chat interface for user interaction

2. **Duration:** 1 Hour

3. **AWS Region:** US East (N. Virginia) — `us-east-1`

   > Ensure that the Amazon Bedrock model is available in this region.

---

# Introduction

## Amazon Bedrock

**Amazon Bedrock** is a fully managed service that simplifies building and scaling generative AI applications using foundation models from leading providers.

It provides access to pre-trained models such as **Amazon Nova Lite** through APIs, eliminating the need to manage the underlying infrastructure.

This enables rapid integration of AI capabilities into applications such as the n8n workflow used in this lab for processing database queries.

---

## AWS RDS (PostgreSQL)

**Amazon RDS — Relational Database Service** provides managed PostgreSQL databases and handles:

- Setup
- Scaling
- Backups
- Maintenance

In this lab, Amazon RDS hosts the PostgreSQL database used by the AI agent to execute SQL queries generated through Amazon Bedrock.

---

## n8n

**n8n** is an open-source workflow automation tool that enables users to build complex workflows using a visual interface.

It supports integrations with AWS services and custom AI-agent nodes, making it suitable for orchestrating:

- Chat triggers
- AI processing
- Conversation memory
- Database operations

---

# Lab Feature

This lab focuses on building an **AI-powered database management agent** using:

- n8n
- Amazon Bedrock
- Amazon RDS
- Amazon EC2

You will:

1. Deploy an EC2 instance with n8n
2. Configure an Amazon RDS PostgreSQL database
3. Set up an n8n workflow
4. Process user queries through a chat interface
5. Use Amazon Bedrock Nova Lite for SQL generation
6. Maintain conversation context and memory

---

# Benefits

## Amazon Bedrock AI Integration

Learn how to use Amazon Bedrock's **Nova Lite** model to dynamically generate SQL queries based on user input.

## n8n Workflow Automation

Gain experience creating workflows with n8n nodes for:

- Chat triggers
- AI processing
- Memory buffering
- Database operations

## RDS PostgreSQL Management

Understand how to set up and connect to a managed PostgreSQL database for secure query execution.

## EC2 Deployment

Learn how to deploy n8n on an Amazon EC2 instance using Docker for workflow hosting.

---

# Architecture Diagram

![Architecture Diagram](image/picture1_34_47.png)

---

# Task Details

1. Sign in to the AWS Management Console
2. Create and configure an Amazon RDS PostgreSQL database with a Security Group
3. Launch an Amazon EC2 instance
4. Deploy n8n using Docker
5. Configure the n8n workflow with nodes and connections
6. Validate the lab

---

# Launching the Lab Environment

## Step 1

Click the **Start Lab** button to launch the lab environment.

## Step 2

Wait for the cloud environment to be provisioned.

Provisioning usually takes less than a minute.

## Step 3

Once the lab starts, you will be provided with:

- IAM Username
- Password
- Access Key
- Secret Access Key

> **Note:** You can start only one lab at a time.
