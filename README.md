# Prompt Directory

Each prompt includes placeholders (e.g., [topic], [task], [constraints]) so you can adapt it to your specific
needs.

## Table of Contents

- [Core Meta Prompts](#core-meta-prompts)
  - [Universal Task Prompt](#universal-task-prompt)
  - [Prompt Design Assistant](#prompt-design-assistant)
  - [Assumption Explorer](#assumption-explorer)
  - [Prompt Critique](#prompt-critique)
  - [Chain-of-Thought Trigger](#chain-of-thought-trigger)
  - [Meta-Prompt Generator](#meta-prompt-generator)

- [Strategy & Decision Making](#strategy--decision-making)
  - [Strategic Analysis](#strategic-analysis)
  - [Decision Framework](#decision-framework)
  - [Risk Matrix Generator](#risk-matrix-generator)
  - [SWOT Prompt](#swot-prompt)
  - [Competitive Landscape Briefing](#competitive-landscape-briefing)
  - [Scenario Planning](#scenario-planning)

- [Business & Product Management](#business--product-management)
  - [Product Requirements Document (PRD) Generator](#product-requirements-document-prd-generator)
  - [Business Model Canvas](#business-model-canvas)
  - [Go-To-Market Plan](#go-to-market-plan)
  - [OKR Creator](#okr-creator)
  - [Stakeholder Mapping](#stakeholder-mapping)
  - [User Persona Builder](#user-persona-builder)
  - [Feature Prioritization](#feature-prioritization)

- [Marketing & Growth](#marketing--growth)
  - [Full-Stack Marketing Campaign](#full-stack-marketing-campaign)
  - [SEO Content Brief](#seo-content-brief)
  - [Audience Segmentation](#audience-segmentation)
  - [Email Campaign Designer](#email-campaign-designer)
  - [Content Repurposing Engine](#content-repurposing-engine)
  - [Brand Voice Finder](#brand-voice-finder)

- [Sales & Negotiation](#sales--negotiation)
  - [Sales Script Builder](#sales-script-builder)
  - [Value Proposition Canvas](#value-proposition-canvas)
  - [Negotiation Playbook](#negotiation-playbook)
  - [Upsell/Cross-Sell Opportunities](#upsellcross-sell-opportunities)
  - [Customer Objection Handling](#customer-objection-handling)

- [Customer Support & Service](#customer-support--service)
  - [Support Response Template](#support-response-template)
  - [FAQ Generator](#faq-generator)
  - [Escalation Protocol](#escalation-protocol)
  - [Knowledge Base Article](#knowledge-base-article)
  - [Customer Feedback Analysis](#customer-feedback-analysis)

- [HR & Talent Management](#hr--talent-management)
  - [Job Description Draft](#job-description-draft)
  - [Interview Question Generator](#interview-question-generator)
  - [Performance Review Template](#performance-review-template)
  - [Onboarding Plan](#onboarding-plan)
  - [Training Program Builder](#training-program-builder)

- [Legal & Compliance (Non-Advice)](#legal--compliance-non-advice)
  - [Contract Summary](#contract-summary)
  - [Privacy Policy Analyzer](#privacy-policy-analyzer)
  - [Compliance Checklist](#compliance-checklist)
  - [Regulatory Change Briefing](#regulatory-change-briefing)

- [Finance & Accounting (Non-Advice)](#finance--accounting-non-advice)
  - [Financial Model Outline](#financial-model-outline)
  - [Budget Planner](#budget-planner)
  - [Unit Economics Calculator](#unit-economics-calculator)
  - [Financial Statement Insights](#financial-statement-insights)
  - [Investment Memo](#investment-memo)

- [AI & Machine Learning](#ai--machine-learning)
  - [ML Model Specification](#ml-model-specification)
  - [Data Preprocessing Plan](#data-preprocessing-plan)
  - [Model Evaluation Report](#model-evaluation-report)
  - [Hyperparameter Tuner](#hyperparameter-tuner)
  - [ML Ethics Checklist](#ml-ethics-checklist)
  - [Responsible AI Communication](#responsible-ai-communication)

- [Software Engineering & DevOps](#software-engineering--devops)
  - [System Architecture Design](#system-architecture-design)
  - [Code Review Checklist](#code-review-checklist)
  - [API Design Specification](#api-design-specification)
  - [DevOps Runbook](#devops-runbook)
  - [Test Suite Plan](#test-suite-plan)
  - [Continuous Delivery Pipeline](#continuous-delivery-pipeline)
  - [Security Hardening Guide](#security-hardening-guide)

- [Data Science & Analytics](#data-science--analytics)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Experiment Design](#experiment-design)
  - [Dashboard Requirements](#dashboard-requirements)
  - [Business Intelligence Questions](#business-intelligence-questions)
  - [Data Pipeline Design](#data-pipeline-design)
  - [Predictive Modeling Plan](#predictive-modeling-plan)

- [Research & Academia](#research--academia)
  - [Literature Review Outline](#literature-review-outline)
  - [Grant Proposal Template](#grant-proposal-template)
  - [Survey Design](#survey-design)
  - [Conference Presentation Prep](#conference-presentation-prep)
  - [Peer Review Checklist](#peer-review-checklist)
  - [Academic Writing Prompt](#academic-writing-prompt)

- [Learning & Education](#learning--education)
  - [Learning Plan](#learning-plan)
  - [Curriculum Outline](#curriculum-outline)
  - [Lesson Plan](#lesson-plan)
  - [Study Guide](#study-guide)
  - [Explainer Prompt](#explainer-prompt)
  - [Educational Quiz Generator](#educational-quiz-generator)

- [Design & UX](#design--ux)
  - [UX Audit](#ux-audit)
  - [Wireframe Brief](#wireframe-brief)
  - [UI Copywriter](#ui-copywriter)
  - [Design System Outline](#design-system-outline)
  - [Accessibility Review](#accessibility-review)

- [Creative Arts & Writing](#creative-arts--writing)
  - [Story Idea Generator](#story-idea-generator)
  - [Scene Writer](#scene-writer)
  - [Poetry Prompt](#poetry-prompt)
  - [Screenplay Outline](#screenplay-outline)
  - [Creative Remix](#creative-remix)
  - [Lyric Generator](#lyric-generator)

- [Health & Wellness (Non-Medical Advice)](#health--wellness-non-medical-advice)
  - [Habit Formation Plan](#habit-formation-plan)
  - [Mindfulness Guide](#mindfulness-guide)
  - [Balanced Meal Plan](#balanced-meal-plan)
  - [Fitness Routine Designer](#fitness-routine-designer)
  - [Sleep Hygiene Checklist](#sleep-hygiene-checklist)

- [Public Speaking & Communication](#public-speaking--communication)
  - [Speech Outline Creator](#speech-outline-creator)
  - [Presentation Design](#presentation-design)
  - [Elevator Pitch Generator](#elevator-pitch-generator)
  - [Media Interview Prep](#media-interview-prep)
  - [Workshop Facilitation Guide](#workshop-facilitation-guide)

- [Productivity & Organization](#productivity--organization)
  - [Time Audit](#time-audit)
  - [Project Timeline Planner](#project-timeline-planner)
  - [Goal Setting Template](#goal-setting-template)
  - [Work-Life Balance Prompt](#work-life-balance-prompt)
  - [Daily Workflow Optimization](#daily-workflow-optimization)

- [Personal Development & Coaching](#personal-development--coaching)
  - [Life Goals Brainstorm](#life-goals-brainstorm)
  - [Strengths & Weaknesses Analysis](#strengths--weaknesses-analysis)
  - [Mentorship Plan](#mentorship-plan)
  - [Values Clarification](#values-clarification)
  - [Career Transition Strategy](#career-transition-strategy)

- [Image Generation & Editing Prompts](#image-generation--editing-prompts)
  - [Universal Image Prompt](#universal-image-prompt)
  - [Product Photography Prompt](#product-photography-prompt)
  - [Character Portrait](#character-portrait)
  - [User Interface Mockup](#user-interface-mockup)
  - [Infographic Design](#infographic-design)

- [Agent & Automation](#agent--automation)
  - [Tool-Using Agent](#tool-using-agent)
  - [Task Orchestration Script](#task-orchestration-script)
  - [Autonomous Research Agent](#autonomous-research-agent)
  - [Systematic Brainstorming Agent](#systematic-brainstorming-agent)
  - [Continuous Improvement Loop](#continuous-improvement-loop)

- [Prompt Engineering & Safety](#prompt-engineering--safety)
  - [Safety Guidelines Prompt](#safety-guidelines-prompt)
  - [Injection Defense](#injection-defense)
  - [Bias Detection Prompt](#bias-detection-prompt)
  - [Evaluation Rubric](#evaluation-rubric)
  - [Hallucination Audit](#hallucination-audit)
  - [Prompt A/B Testing](#prompt-ab-testing)

- [Environmental & Sustainability](#environmental--sustainability)
  - [Sustainability Strategy Plan](#sustainability-strategy-plan)
  - [Carbon Footprint Assessment](#carbon-footprint-assessment)
  - [Circular Economy Business Model](#circular-economy-business-model)
  - [Environmental Impact Report](#environmental-impact-report)
  - [Sustainable Procurement Guidelines](#sustainable-procurement-guidelines)

- [Social Impact & Philanthropy](#social-impact--philanthropy)
  - [Social Impact Strategy](#social-impact-strategy)
  - [CSR Program Design](#csr-program-design)
  - [Fundraising Campaign Plan](#fundraising-campaign-plan)
  - [Nonprofit Impact Measurement](#nonprofit-impact-measurement)
  - [Stakeholder Engagement Plan](#stakeholder-engagement-plan)

- [Political & Policy Analysis (Non-Advocacy)](#political--policy-analysis-non-advocacy)
  - [Policy Brief Template](#policy-brief-template)
  - [Legislative Analysis](#legislative-analysis)
  - [Political Risk Assessment](#political-risk-assessment)
  - [Voter Sentiment Report](#voter-sentiment-report)
  - [Campaign Messaging Framework](#campaign-messaging-framework)

- [Travel & Tourism](#travel--tourism)
  - [Travel Itinerary Builder](#travel-itinerary-builder)
  - [Destination Research Report](#destination-research-report)
  - [Travel Budget Planner](#travel-budget-planner)
  - [Sustainable Tourism Guidelines](#sustainable-tourism-guidelines)
  - [Travel Safety Checklist](#travel-safety-checklist)

- [Event Planning & Hospitality](#event-planning--hospitality)
  - [Event Concept Development](#event-concept-development)
  - [Venue Selection Criteria](#venue-selection-criteria)
  - [Catering Plan](#catering-plan)
  - [Guest Experience Design](#guest-experience-design)
  - [Event Marketing Plan](#event-marketing-plan)

- [Real Estate & Urban Planning](#real-estate--urban-planning)
  - [Market Analysis for Real Estate](#market-analysis-for-real-estate)
  - [Property Development Proposal](#property-development-proposal)
  - [Urban Renewal Assessment](#urban-renewal-assessment)
  - [Housing Needs Study](#housing-needs-study)
  - [Green Building Guide](#green-building-guide)

- [Supply Chain & Operations](#supply-chain--operations)
  - [Supply Chain Optimization Plan](#supply-chain-optimization-plan)
  - [Inventory Management SOP](#inventory-management-sop)
  - [Procurement Risk Assessment](#procurement-risk-assessment)
  - [Logistics Strategy](#logistics-strategy)
  - [Vendor Management Framework](#vendor-management-framework)

- [Customer Experience & Loyalty](#customer-experience--loyalty)
  - [Customer Journey Improvement Plan](#customer-journey-improvement-plan)
  - [Loyalty Program Design](#loyalty-program-design)
  - [Voice of Customer Analysis](#voice-of-customer-analysis)
  - [Net Promoter Score Action Plan](#net-promoter-score-action-plan)
  - [Service Recovery Blueprint](#service-recovery-blueprint)

- [E-learning & Edtech](#e-learning--edtech)
  - [Online Course Blueprint](#online-course-blueprint)
  - [EdTech Product Evaluation](#edtech-product-evaluation)
  - [Virtual Classroom Management](#virtual-classroom-management)
  - [Interactive Lesson Design](#interactive-lesson-design)
  - [EdTech Adoption Strategy](#edtech-adoption-strategy)

- [Gamification & Game Design](#gamification--game-design)
  - [Game Concept Document](#game-concept-document)
  - [Gamification Strategy](#gamification-strategy)
  - [Level Design Guide](#level-design-guide)
  - [Player Retention Analysis](#player-retention-analysis)
  - [Narrative Design Outline](#narrative-design-outline)

- [Rapid Prompt Bank](#rapid-prompt-bank)



### Assumption Explorer

When given a prompt, identify all implicit assumptions. Classify each assumption as critical, neutral, or
optional. Suggest ways to test or validate each critical assumption.

### Prompt Critique

Act as a senior prompt engineer. Evaluate the following prompt: [prompt text]. Identify strengths,
weaknesses, biases, and missing details. Suggest revisions to improve clarity, scope, and safety.

### Chain-of-Thought Trigger

Encourage the model to think step-by-step: [task description]. Provide guidance on breaking down the
problem, reasoning through substeps, and justifying the final answer.

### Meta-Prompt Generator

Generate meta-prompts that help users create better prompts for [domain]. Each meta-prompt should
instruct the user on how to specify role, context, and constraints.

## Strategy & Decision Making

### Strategic Analysis

Act as a senior strategist. Analyze [plan/idea/business] focusing on weaknesses, market risks, hidden
assumptions, and competitive threats. Propose strategic alternatives and a prioritized action plan for
improvement.

### Decision Framework

Evaluate the decision scenario: [description]. List available options, and for each describe best, worst, and
likely outcomes, second-order effects, hidden biases, and a final recommendation. Suggest questions the
decision maker might be missing.

### Risk Matrix Generator

Generate a risk matrix for [project/decision] identifying potential risks, their probability, impact, mitigation
strategies, and early warning signals.

### SWOT Prompt

Conduct a SWOT analysis for [company/product/initiative]. List strengths, weaknesses, opportunities, and
threats. For each category provide brief reasoning and supporting evidence.


### Competitive Landscape Briefing

Research competitors in [industry/market]. Summarize each competitor's target audience, positioning,
pricing, marketing tactics, strengths, weaknesses, and opportunities for differentiation.

### Scenario Planning

Develop three plausible scenarios for [future situation]. For each scenario describe key drivers,
assumptions, outcomes, opportunities, and risks. Recommend strategies to prepare or adapt.

## Business & Product Management

### Product Requirements Document (PRD) Generator

Create a PRD for [product name]. Include product vision, target users, problems solved, key features, user
stories, acceptance criteria, metrics, and risks.

### Business Model Canvas

Fill out a business model canvas for [business idea], covering value proposition, customer segments,
channels, revenue streams, key activities, resources, partners, cost structure, and success metrics.

### Go-To-Market Plan

Develop a go-to-market plan for [product/service]. Outline market segmentation, positioning, pricing
strategy, distribution channels, customer acquisition tactics, budget allocation, and success metrics.

### OKR Creator

Design OKRs (Objectives and Key Results) for [team/project/quarter]. Specify high-level objectives,
measurable key results, deadlines, and owners. Provide guidance on alignment and tracking.

### Stakeholder Mapping

Identify key stakeholders for [initiative/project]. Classify them by influence and interest. Describe their
needs, pain points, and engagement strategies.

### User Persona Builder

Create detailed user personas for [product/service]. Include demographics, goals, behaviors, pain points,
and preferred channels. Generate at least three distinct personas.

### Feature Prioritization

Prioritize a list of features for [product] based on impact, effort, and user value. Provide a prioritization
matrix and reasoning for each ranking.


## Marketing & Growth

### Full-Stack Marketing Campaign

You are a senior marketing strategist, copywriter, and content planner. Product: [description]; Audience:
[target]; Price: [amount]. Create a 14-day marketing campaign including daily social posts (complete copy),
email sequences (welcome + nurturing + sales), video hook ideas, and a 30-day content calendar.

### SEO Content Brief

Generate an SEO content brief for the keyword/topic [keyword]. Include search intent, target audience, top
search questions, outline, recommended word count, semantic keywords, and internal/external linking
strategy.

### Audience Segmentation

Segment the audience for [product/service] into distinct groups based on demographics, behaviors,
psychographics, and purchase intent. Describe each segment and tailor a unique messaging strategy.

### Email Campaign Designer

Design an email campaign for [objective]. Outline the campaign flow, subject lines, body copy,
personalization tactics, calls-to-action, and metrics to track.

### Content Repurposing Engine

Take source content: [link/text] and repurpose it into a multi-platform marketing suite: a Twitter/X thread, a
LinkedIn post, an Instagram caption (with emojis and CTA), three short-form video scripts, and an email
newsletter. Ensure each piece feels native to its platform.

### Brand Voice Finder

Analyze the brand materials for [company]. Describe the brand voice, tone, key phrases, and style
guidelines. Create a writing guide with examples and do's & don'ts.

## Sales & Negotiation

### Sales Script Builder

Construct a sales script for [product/service] aimed at [buyer persona]. Include opening, qualification
questions, value proposition statements, handling objections, closing techniques, and follow-up
suggestions.


### Value Proposition Canvas

Create a value proposition canvas for [product/service]. Map customer jobs, pains, and gains to product
features, pain relievers, and gain creators. Summarize key insights.

### Negotiation Playbook

Develop a negotiation strategy for [scenario]. Identify goals, walk-away points, concessions, questions to
ask, and persuasive arguments. Predict counterarguments and outline responses.

### Upsell/Cross-Sell Opportunities

Identify upsell and cross-sell opportunities for [company/product]. Segment customers based on purchase
history and preferences. Design targeted offers and messaging for each segment.

### Customer Objection Handling

List common objections for [product/service]. Provide effective responses, evidence points, and question
prompts to keep conversations moving forward.

## Customer Support & Service

### Support Response Template

Write a professional support response for [customer issue]. Acknowledge the issue, empathize with the
customer, provide a clear resolution or workaround, offer next steps, and invite feedback.

### FAQ Generator

Generate a comprehensive FAQ for [product/service]. List common questions, succinct answers,
troubleshooting tips, and links to further resources.

### Escalation Protocol

Design a customer support escalation protocol for [company]. Define tiers of support, criteria for escalation,
resolution timelines, and communication best practices.

### Knowledge Base Article

Draft a knowledge base article for [topic]. Provide a concise overview, step-by-step instructions, screenshots
or diagrams if relevant, common pitfalls, and helpful resources.

### Customer Feedback Analysis

Analyze customer feedback data for [time period/product]. Identify themes, sentiment trends, most
common complaints, and improvement opportunities. Suggest actions to enhance the customer
experience.


## HR & Talent Management

### Job Description Draft

Create a detailed job description for [role]. Include responsibilities, required skills, preferred experience, key
outcomes, benefits, and company culture.

### Interview Question Generator

Generate tailored interview questions for [role]. Cover technical skills, behavioral competencies, situational
judgement, and culture fit. Indicate what a good answer looks like.

### Performance Review Template

Draft a performance review form for [position]. Include areas for strengths, growth, goal achievement, peer
feedback, and development plans.

### Onboarding Plan

Design a 90-day onboarding plan for [new hire role]. Outline milestones, training topics, mentors, and
success metrics for each phase.

### Training Program Builder

Outline a training program for [skill/topic]. Include learning objectives, curriculum modules, delivery
methods, evaluation criteria, and expected outcomes.

## Legal & Compliance (Non-Advice)

### Contract Summary

Summarize the key clauses in the following contract: [text]. Highlight obligations, deliverables, payment
terms, termination conditions, liability limitations, and dispute resolution methods. Note ambiguous
clauses and potential negotiation points. _Disclaimer: This prompt is for informational purposes and does not
constitute legal advice._

### Privacy Policy Analyzer

Analyze the privacy policy of [company/website]. Identify data collection practices, sharing policies, user
rights, retention periods, and compliance with regulations (e.g., GDPR, CCPA). _Disclaimer: This prompt is for
informational purposes and does not constitute legal advice._


### Compliance Checklist

Create a compliance checklist for [industry/regulation]. List critical requirements, documentation needed,
responsible roles, and recommended review intervals. _Disclaimer: This prompt is for informational purposes
and does not constitute legal advice._

### Regulatory Change Briefing

Brief on recent changes in [law/regulation] relevant to [industry]. Explain key updates, effective dates,
impacted entities, and recommended actions to ensure compliance. _Disclaimer: This prompt is for
informational purposes and does not constitute legal advice._

## Finance & Accounting (Non-Advice)

### Financial Model Outline

Outline a financial model for [business/project]. Include revenue streams, cost structure, forecasting
assumptions, cash flow projections, and sensitivity analysis. _Disclaimer: This prompt is for informational
purposes and does not constitute financial advice._

### Budget Planner

Create a budget plan for [department/project/time period]. List income sources, expense categories,
planned vs. actual tracking, and contingency plans. _Disclaimer: This prompt is for informational purposes and
does not constitute financial advice._

### Unit Economics Calculator

Calculate unit economics for [product/service]. Define customer acquisition cost (CAC), lifetime value (LTV),
gross margin, payback period, and break-even point. _Disclaimer: This prompt is for informational purposes
and does not constitute financial advice._

### Financial Statement Insights

Analyze the financial statements of [company] for the last [period]. Highlight revenue trends, profitability,
liquidity ratios, and risk factors. _Disclaimer: This prompt is for informational purposes and does not constitute
financial advice._

### Investment Memo

Draft an investment memo for [startup/company]. Include market opportunity, team assessment, product
differentiation, traction metrics, financial projections, and risks. _Disclaimer: This prompt is for informational
purposes and does not constitute financial advice._


## AI & Machine Learning

### ML Model Specification

Specify requirements for a machine learning model for [task/domain]. Describe the problem, dataset
characteristics, target variable, evaluation metrics, and constraints (e.g., fairness, interpretability). Outline
the model architecture and training plan.

### Data Preprocessing Plan

Create a data preprocessing pipeline for [dataset]. Describe steps for cleaning, handling missing values,
encoding categorical variables, normalization, and feature engineering.

### Model Evaluation Report

Generate a model evaluation report for [model]. Include performance metrics (accuracy, precision, recall,
F1, AUC), confusion matrix, cross-validation summary, and bias analysis. Highlight strengths, limitations,
and recommended improvements.

### Hyperparameter Tuner

Create a hyperparameter tuning plan for [algorithm]. List parameters to tune, search space, optimization
method (grid search, random search, Bayesian), and evaluation strategy.

### ML Ethics Checklist

Develop an ethics checklist for deploying [AI system]. Cover fairness, transparency, accountability, user
privacy, bias mitigation, and compliance with applicable regulations.

### Responsible AI Communication

Draft a communication plan for disclosing AI usage in [product/service]. Describe how to inform users
about AI involvement, data usage, decision logic, and opt-out mechanisms.

## Software Engineering & DevOps

### System Architecture Design

Design the high-level architecture for [system/application]. Identify major components, data flow,
technology stack, scalability considerations, security measures, and trade-offs. Provide an accompanying
diagram description.

### Code Review Checklist

Review the following code: [code snippet]. Identify bugs, security vulnerabilities, performance issues, code
smells, and opportunities for refactoring. Suggest specific improvements and best practices.


### API Design Specification

Specify a REST/GraphQL API for [service]. Define endpoints, request/response schemas, authentication,
error handling, rate limiting, and versioning.

### DevOps Runbook

Create an incident response runbook for [system]. Include detection methods, communication channels,
mitigation steps, rollback procedures, postmortem process, and documentation templates.

### Test Suite Plan

Develop a test suite for [project]. Define unit tests, integration tests, end-to-end tests, performance tests,
and security tests. Include test coverage goals and reporting cadence.

### Continuous Delivery Pipeline

Design a CI/CD pipeline for [application]. Specify stages (build, test, deploy), automation tools, branching
strategy, rollback mechanisms, and deployment environments.

### Security Hardening Guide

Provide a security hardening guide for [application/system]. Cover access control, encryption, secure coding
practices, vulnerability scanning, patch management, and compliance with standards.

## Data Science & Analytics

### Exploratory Data Analysis (EDA)

Conduct an EDA on [dataset]. Describe data types, missing values, distributions, correlations, outliers, and
key insights. Visualize important patterns and highlight anomalies.

### Experiment Design

Design an experiment to test [hypothesis]. Specify independent and dependent variables, control and
treatment groups, sample size, randomization, and statistical tests.

### Dashboard Requirements

Gather requirements for a dashboard tracking [metrics/process]. List key metrics, data sources,
visualizations, filters, user roles, and update frequency.

### Business Intelligence Questions

Generate a list of BI questions for [department/company]. Cover revenue, operations, customer behavior,
marketing effectiveness, and risk. For each question suggest appropriate data sources.


### Data Pipeline Design

Design a data pipeline to ingest, process, and deliver [data type]. Describe data sources, extraction
methods, transformation steps, storage, quality checks, and downstream consumers.

### Predictive Modeling Plan

Outline a predictive modeling plan for [objective]. Define the target variable, feature selection approach,
algorithms to evaluate, validation strategy, and success metrics.

## Research & Academia

### Literature Review Outline

Draft an outline for a literature review on [topic]. Identify key themes, seminal papers, research gaps,
controversies, and future research directions.

### Grant Proposal Template

Create a template for a grant proposal for [project]. Include abstract, objectives, methodology, expected
outcomes, budget summary, team qualifications, and evaluation plan.

### Survey Design

Design a survey to collect data on [topic]. Define objectives, target population, sampling method, question
types, and ethical considerations.

### Conference Presentation Prep

Provide a structure for preparing a conference presentation on [research topic]. Outline introduction,
methods, results, discussion, conclusion, visuals, and Q&A preparation.

### Peer Review Checklist

Generate a peer review checklist for evaluating a research paper. Cover originality, methodology,
significance, clarity, data quality, ethics, and constructive feedback.

### Academic Writing Prompt

Write an academic abstract for a paper on [topic]. Include background, methods, results, and conclusions in
250 words.


## Learning & Education

### Learning Plan

Create a personalized learning plan to master [subject/skill] in [time period]. Include learning objectives, key
resources, daily/weekly schedule, practice activities, and assessment methods.

### Curriculum Outline

Outline a curriculum for teaching [topic] to [audience level]. Break down the curriculum into modules,
learning objectives, lessons, assessments, and required materials.

### Lesson Plan

Develop a lesson plan for [topic] lasting [duration]. Specify learning goals, warm-up activity, core
instruction, interactive exercises, and evaluation.

### Study Guide

Create a study guide for [exam/course]. Summarize key concepts, formulas, diagrams, practice questions,
and study tips.

### Explainer Prompt

Explain [concept] at three levels: (1) to a child; (2) to a peer; (3) to an expert. Highlight nuances and common
misconceptions at each level.

### Educational Quiz Generator

Generate a quiz on [topic] with [n] multiple-choice questions. Provide correct answers and brief
explanations.

## Design & UX

### UX Audit

Conduct a UX audit for [website/app]. Analyze usability, accessibility, information architecture, visual design,
and conversion pathways. Provide prioritized recommendations for improvement.

### Wireframe Brief

Write a brief for creating wireframes for [page/flow]. Describe the goal, key elements, user personas, user
scenarios, and success criteria.


### UI Copywriter

Write microcopy for [feature/page] focusing on clarity, brevity, and user motivation. Include buttons,
tooltips, error messages, and success states.

### Design System Outline

Draft an outline for a design system for [brand]. Cover typography, color palette, spacing, component
library, iconography, motion guidelines, and documentation.

### Accessibility Review

Review [app/site] for accessibility compliance (WCAG). Identify issues with color contrast, keyboard
navigation, screen reader support, and provide remediation guidance.

## Creative Arts & Writing

### Story Idea Generator

Generate story ideas in the genre [genre] featuring [themes]. Provide five distinct ideas with protagonist,
setting, conflict, and twist.

### Scene Writer

Write a vivid scene where [character] faces [challenge]. Use descriptive language, sensory details, and
dialogue. Keep it under 500 words.

### Poetry Prompt

Compose a poem on the theme [theme]. Specify style (haiku, sonnet, free verse), tone, imagery, and any
structural constraints.

### Screenplay Outline

Outline a screenplay with three acts for [story]. Describe major plot points, character arcs, settings, and
tone.

### Creative Remix

Take the plot of [classic story] and remix it in a new genre [genre]. Explain how the characters, setting, and
themes adapt to the new genre.

### Lyric Generator

Write song lyrics on the topic [topic] in the style of [artist/genre]. Include verses, chorus, and bridge with
rhyme and rhythm.


## Health & Wellness (Non-Medical Advice)

### Habit Formation Plan

Create a habit formation plan for [habit]. Outline triggers, implementation intentions, tracking methods,
rewards, and accountability. _Disclaimer: This prompt is for general informational purposes and does not
constitute medical advice._

### Mindfulness Guide

Draft a mindfulness practice guide for [purpose] (e.g., stress reduction, focus). Include breathing exercises,
meditation prompts, journaling questions, and recommended frequency. _Disclaimer: This prompt is for
general informational purposes and does not constitute medical advice._

### Balanced Meal Plan

Outline a weekly meal plan supporting [goal] (e.g., energy, balanced nutrition). Include variety, portion
guidance, and shopping list suggestions. _Disclaimer: This prompt is for general informational purposes and
does not constitute medical advice._

### Fitness Routine Designer

Design a fitness routine for [level] to achieve [goal]. Specify workout types, duration, frequency, and
recovery tips. _Disclaimer: This prompt is for general informational purposes and does not constitute medical
advice._

### Sleep Hygiene Checklist

Provide a sleep hygiene checklist to improve sleep quality. Include pre-sleep routines, environment
adjustments, and lifestyle recommendations. _Disclaimer: This prompt is for general informational purposes
and does not constitute medical advice._

## Public Speaking & Communication

### Speech Outline Creator

Outline a speech on [topic] for [audience]. Define opening hook, main points, supporting evidence,
storytelling elements, conclusion, and call to action.

### Presentation Design

Design a slide deck for [presentation topic]. Provide an outline of slides, key content for each, visuals to
include, and speaker notes.


### Elevator Pitch Generator

Craft an elevator pitch for [idea/product/company]. Keep it under 60 seconds and highlight the problem,
solution, differentiation, and call to action.

### Media Interview Prep

Prepare for a media interview on [subject]. List likely questions, key messages, supportive facts, bridging
statements, and soundbites.

### Workshop Facilitation Guide

Develop a facilitation guide for a workshop on [topic]. Detail agenda, interactive activities, group discussion
prompts, materials needed, and feedback methods.

## Productivity & Organization

### Time Audit

Conduct a time audit for [period]. List all activities, categorize them (deep work, admin, meetings, personal),
compute time spent, and identify low-value tasks to delegate or eliminate.

### Project Timeline Planner

Create a project timeline for [project name]. Define tasks, milestones, dependencies, estimated durations,
responsible parties, and deliverables.

### Goal Setting Template

Set SMART goals for [objective]. Include specific outcomes, measurement criteria, accountability partners,
timeframes, and progress checkpoints.

### Work-Life Balance Prompt

Reflect on current work-life balance. Identify areas of imbalance, root causes, and actions to improve
alignment with personal values and priorities.

### Daily Workflow Optimization

Design a daily workflow for maximizing productivity while maintaining wellbeing. Include morning routine,
work blocks, breaks, reflection, and end-of-day review.


## Personal Development & Coaching

### Life Goals Brainstorm

Brainstorm life goals across categories (career, relationships, health, learning, hobbies, contribution). Write
down aspirations without judgment, then prioritize top 5 goals and define first steps.

### Strengths & Weaknesses Analysis

Identify personal strengths and weaknesses for [individual/team]. Provide examples, potential impact, and
strategies to leverage or address them.

### Mentorship Plan

Create a mentorship plan for [mentee]. Outline goals, areas of focus, meeting cadence, feedback process,
and success indicators.

### Values Clarification

Guide someone through a values clarification exercise. List core values, provide prompts to explore why
each matters, and reflect on alignment with actions.

### Career Transition Strategy

Develop a strategy for transitioning from [current role] to [target role]. Identify transferable skills, skills
gaps, training opportunities, networking targets, and timeline.

## Image Generation & Editing Prompts

### Universal Image Prompt

Subject: [primary subject] Scene: [background/setting] Composition: [framing/angle] Lighting: [type/
intensity] Style: [artistic style] Mood: [emotions/atmosphere] Camera: [lens/focal length] Constraints:
[specific guidelines] Negative prompts: [elements to avoid]

### Product Photography Prompt

Generate a prompt for photographing [product] for [brand/marketplace]. Include studio lighting setup,
background style, composition variations, and mood instructions.

### Character Portrait

Create an image prompt for a character portrait. Define the character's appearance, clothing style,
expression, and environment. Specify art style and color palette.


### User Interface Mockup

Write a prompt to generate a realistic UI mockup for [app type] targeting [users] on [platform]. Detail layout
system, typography, color scheme, and core screens.

### Infographic Design

Describe a prompt for generating an infographic visualizing [data concept]. Include chart types, icons, color
palette, and composition guidance.

## Agent & Automation

### Tool-Using Agent

Act as a multi-tool agent tasked with achieving [goal]. You have access to tools: [list]. Iterate in a loop: (plan
→ act → evaluate → adjust) until the goal is met. Ensure safe use of tools and logging of actions.

### Task Orchestration Script

Generate a script to automate tasks for [workflow]. Describe each step, required tools or APIs, error
handling, logging, and completion criteria.

### Autonomous Research Agent

Design an autonomous agent that performs research on [topic]. Specify how it gathers sources,
summarizes findings, tracks citations, and synthesizes insights. Include safety checks and stopping
conditions.

### Systematic Brainstorming Agent

Develop a brainstorming agent that generates multiple ideas for [problem]. Outline how it explores
different perspectives, filters for feasibility, and clusters ideas.

### Continuous Improvement Loop

Design an agent that continually improves [process/product]. Specify how it collects data, identifies
bottlenecks, experiments with improvements, and reports results.

## Prompt Engineering & Safety

### Safety Guidelines Prompt

List safety guidelines to follow when designing prompts for high impact domains (health, finance, legal).
Include considerations such as fairness, transparency, harm minimization, and compliance.


### Injection Defense

Design a procedure to prevent prompt injection attacks. Outline rules for sanitizing user input, isolating
instructions, and validating outputs.

### Bias Detection Prompt

Create a prompt for detecting biases in generated text. Specify target biases (gender, race, etc.), evaluation
criteria, and mitigation suggestions.

### Evaluation Rubric

Develop a rubric for evaluating prompt quality. Include clarity, completeness, ethical considerations,
diversity & inclusion, and alignment with objectives.

### Hallucination Audit

Design a workflow to audit outputs for hallucinations. Describe how to verify factual accuracy, track sources,
and flag unsupported claims.

### Prompt A/B Testing

Outline an A/B testing framework for comparing two prompts on [task]. Define metrics (accuracy, user
satisfaction, response time), sample size, randomization, and statistical analysis.

## Environmental & Sustainability

### Sustainability Strategy Plan

Develop a sustainability strategy for [organization/project]. Set long-term goals, metrics (e.g., emissions
reduction, resource efficiency), action items, timelines, stakeholders, and accountability mechanisms.

### Carbon Footprint Assessment

Provide a framework for estimating the carbon footprint of [activity/product/operation]. Identify emission
sources, data collection methods, calculation formulas, and reduction strategies.

### Circular Economy Business Model

Design a circular economy model for [product/company]. Describe product lifecycle, reuse/recycling
processes, partnerships, and revenue mechanisms.

### Environmental Impact Report

Draft an environmental impact assessment for [project]. Analyze impacts on air, water, soil, biodiversity, and
local communities. Recommend mitigation and monitoring measures.


### Sustainable Procurement Guidelines

Create procurement guidelines to ensure sustainable sourcing. Include criteria for suppliers (e.g., ethical
labor, low carbon), evaluation process, and audit requirements.

## Social Impact & Philanthropy

### Social Impact Strategy

Develop a social impact strategy for [organization/initiative]. Define mission objectives, beneficiary groups,
programs, and impact metrics.

### CSR Program Design

Design a corporate social responsibility program for [company]. Outline focus areas (e.g., education,
environment), partnerships, employee engagement, and reporting.

### Fundraising Campaign Plan

Create a plan for fundraising campaign [campaign name]. Define target donors, messaging, channels,
events, timeline, and success metrics.

### Nonprofit Impact Measurement

Develop a framework for measuring the impact of [nonprofit program]. Identify outputs, outcomes, data
collection methods, and analysis techniques.

### Stakeholder Engagement Plan

Outline an engagement plan for stakeholders in [social project]. Segment stakeholders, tailor
communication, gather feedback, and manage expectations.

## Political & Policy Analysis (Non-Advocacy)

### Policy Brief Template

Draft a policy brief on [issue]. Include problem statement, background, policy options, benefits, drawbacks,
and recommendations. _Disclaimer: Informational only; does not constitute legal or political advice._

### Legislative Analysis

Analyze proposed legislation [bill name/number]. Summarize key provisions, stakeholders, potential
impacts, and implementation considerations. _Disclaimer: Informational only; does not constitute legal or
political advice._


### Political Risk Assessment

Conduct a political risk assessment for investing/operating in [country]. Evaluate stability, regulatory
environment, corruption levels, and potential disruptions.

### Voter Sentiment Report

Create a report on voter sentiment around [topic/election]. Analyze polling data, demographic trends,
media narratives, and key issues.

### Campaign Messaging Framework

Develop a messaging framework for a political campaign on [issue]. Identify target audiences, core
messages, channels, and tone guidelines. _Disclaimer: Informational only; does not constitute political advice._

## Travel & Tourism

### Travel Itinerary Builder

Build a customized travel itinerary for [destination] lasting [duration]. Include attractions, dining, lodging,
transportation, and daily schedule.

### Destination Research Report

Compile a research report on [destination]. Cover history, culture, climate, key sights, cuisine, local customs,
and travel tips.

### Travel Budget Planner

Plan a budget for a trip to [destination]. Estimate costs for flights, accommodation, food, activities,
insurance, and contingencies.

### Sustainable Tourism Guidelines

Draft guidelines for practicing sustainable tourism in [region]. Focus on minimizing environmental impact,
respecting local communities, and supporting conservation efforts.

### Travel Safety Checklist

Create a safety checklist for travelers to [destination]. Include health considerations, emergency contacts,
local laws, and risk mitigation tips.


## Event Planning & Hospitality

### Event Concept Development

Develop a concept for [event type]. Define goals, theme, target audience, activities, and unique elements.

### Venue Selection Criteria

Outline criteria for selecting a venue for [event]. Consider capacity, location, accessibility, facilities, cost, and
ambiance.

### Catering Plan

Create a catering plan for [event]. Include menu options, dietary considerations, serving style, and vendor
coordination.

### Guest Experience Design

Design the guest experience for [event]. Map out arrival, engagement activities, comforts, and memorable
touches throughout the event.

### Event Marketing Plan

Develop a marketing plan to promote [event]. Define channels (social, email, PR), messaging, partnerships,
timeline, and success metrics.

## Real Estate & Urban Planning

### Market Analysis for Real Estate

Conduct a market analysis for real estate in [location]. Evaluate supply/demand, pricing trends,
demographics, and competitor projects.

### Property Development Proposal

Draft a proposal for developing [property/project]. Include project vision, zoning analysis, feasibility study,
design concept, and financial projections.

### Urban Renewal Assessment

Assess urban renewal opportunities in [area]. Consider infrastructure, community needs, environmental
impact, and potential economic benefits.


### Housing Needs Study

Perform a housing needs assessment for [community]. Analyze demographics, affordability, housing stock
quality, and policy implications.

### Green Building Guide

Create guidelines for designing green buildings. Cover energy efficiency, sustainable materials, water
management, and certification standards.

## Supply Chain & Operations

### Supply Chain Optimization Plan

Develop a plan to optimize the supply chain for [company/product]. Analyze current processes, identify
bottlenecks, recommend improvements, and quantify expected benefits.

### Inventory Management SOP

Write a standard operating procedure for inventory management. Define reorder points, safety stock, cycle
counting, and inventory tracking methods.

### Procurement Risk Assessment

Conduct a risk assessment of procurement for [organization]. Identify supply risks, geopolitical factors,
supplier dependencies, and mitigation strategies.

### Logistics Strategy

Formulate a logistics strategy for distributing [product]. Determine shipping modes, routing optimization,
warehousing, and cost trade-offs.

### Vendor Management Framework

Create a framework for managing vendors and suppliers. Include selection criteria, performance metrics,
communication cadence, and contract review processes.

## Customer Experience & Loyalty

### Customer Journey Improvement Plan

Propose improvements to the customer journey for [product/service]. Identify pain points, recommend
enhancements, and prioritize initiatives based on impact and effort.


### Loyalty Program Design

Design a customer loyalty program for [brand]. Define tiers, rewards, earning mechanisms, redemption
rules, and communication strategy.

### Voice of Customer Analysis

Conduct a voice of customer analysis using feedback sources (surveys, reviews, support tickets). Identify
themes, sentiment, and actionable insights to improve customer satisfaction.

### Net Promoter Score Action Plan

Develop an action plan to improve Net Promoter Score for [company]. Segment detractors, passives,
promoters; analyze root causes; and define targeted interventions.

### Service Recovery Blueprint

Create a blueprint for service recovery when things go wrong. Outline apology protocols, compensation
guidelines, internal escalation, and follow-up.

## E-learning & Edtech

### Online Course Blueprint

Design a blueprint for an online course on [subject]. Outline course objectives, modules, content formats,
assessment methods, and learner engagement strategies.

### EdTech Product Evaluation

Evaluate an EdTech product for [use case]. Assess user experience, pedagogical soundness, accessibility,
scalability, and data privacy compliance.

### Virtual Classroom Management

Create a guide for managing virtual classrooms. Include best practices for engagement, moderation,
technical troubleshooting, and learner support.

### Interactive Lesson Design

Design an interactive lesson on [topic]. Incorporate multimedia elements, quizzes, discussions, and hands-
on activities to enhance understanding.

### EdTech Adoption Strategy

Develop a strategy to adopt EdTech solutions in [institution]. Address technology infrastructure, stakeholder
buy-in, training, and evaluation metrics.


## Gamification & Game Design

### Game Concept Document

Draft a concept document for a game themed around [subject/genre]. Describe core mechanics, player
objectives, art style, and unique selling points.

### Gamification Strategy

Develop a gamification strategy to encourage [behavior] in [context]. Define game elements (points,
badges, leaderboards), progression system, rewards, and feedback loops.

### Level Design Guide

Write a level design guide for [game]. Detail level objectives, difficulty curves, pacing, environmental
storytelling, and player testing considerations.

### Player Retention Analysis

Analyze player retention data for [game/app]. Identify drop-off points, retention drivers, and strategies to
improve long-term engagement.

### Narrative Design Outline

Create a narrative design outline for [game/story]. Include world-building, character arcs, branching
choices, and narrative pacing.

## Rapid Prompt Bank

### Rapid Prompt 1 — Summarize

Summarize [document/text] in [number] bullet points. Highlight key themes, statistics, and action items.

### Rapid Prompt 2 — Translate

Translate the following text to [language], preserving tone and nuance: [input text].

### Rapid Prompt 3 — Explain Concept

Explain [topic] to a beginner. Use analogies and simple language.

### Rapid Prompt 4 — Compare

Compare [option A] and [option B] across dimensions: [criteria]. Provide pros and cons and recommend
one.


### Rapid Prompt 5 — Generate Ideas

Generate [number] creative ideas for [problem/challenge], including unconventional approaches.

### Rapid Prompt 6 — Outline

Create an outline for a [report/article/presentation] on [topic]. Include main sections and supporting points.

### Rapid Prompt 7 — Rewrite for Audience

Rewrite the text for [audience persona] with an appropriate tone and reading level.

### Rapid Prompt 8 — Create Checklist

Make a checklist for [procedure]. List steps, required materials, and success criteria.

### Rapid Prompt 9 — Design Survey

Design a short survey to gather feedback on [subject]. Include multiple choice and open questions.

### Rapid Prompt 10 — Plan Event

Plan an event for [occasion/audience]. Determine budget, agenda, logistics, and promotional strategy.

### Rapid Prompt 11 — Diagnostic Questions

List diagnostic questions to identify the root cause of [issue/problem].

### Rapid Prompt 12 — Brainstorm Keywords

Brainstorm keywords and hashtags for promoting [topic] on social media.

### Rapid Prompt 13 — Code Snippet

Write a code snippet in [language] to [achieve task]. Include comments explaining each step.

### Rapid Prompt 14 — Storyboard

Create a storyboard for a [video/ad] about [message]. Describe scenes, dialogue, and visuals.

### Rapid Prompt 15 — Prepare Interview

Prepare an interview guide to hire a [position]. Include structured questions and evaluation criteria.


### Rapid Prompt 16 — Launch Checklist

Develop a launch checklist for [product]. Cover pre-launch tasks, launch day actions, and post-launch
monitoring.

### Rapid Prompt 17 — Write Press Release

Write a press release announcing [event/product]. Include headline, subheading, body, quotes, and contact
info.

### Rapid Prompt 18 — Assess Competency

Draft a rubric to assess competency in [skill]. Define proficiency levels and observable behaviors.

### Rapid Prompt 19 — Calculate Metric

Describe how to calculate [metric] and interpret the result. Provide an example scenario.

### Rapid Prompt 20 — Social Media Calendar

Create a 14-day social media content calendar for [brand/campaign]. Specify platform, post type, and key
message for each day.

### Rapid Prompt 21 — Facilitate Brainstorm

Facilitate a brainstorming session on [topic]. Outline rules, prompts, and evaluation criteria for ideas.

### Rapid Prompt 22 — Argument Analysis

Analyze an argument about [topic]. Identify premises, conclusion, assumptions, and logical fallacies.

### Rapid Prompt 23 — Write Email Response

Compose a professional email response to [situation]. Clarify expectations, provide next steps, and maintain
a positive tone.

### Rapid Prompt 24 — Problem-Solving Steps

Outline the steps to solve [problem]. Include data gathering, analysis, solution generation, and evaluation.

### Rapid Prompt 25 — Debate Preparation

Prepare talking points for a debate on [issue]. List supporting arguments, counterarguments, and evidence.


### Rapid Prompt 26 — SOP Template

Draft a standard operating procedure for [process]. Include purpose, scope, responsibilities, steps, and
KPIs.

### Rapid Prompt 27 — Marketing Persona

Create a marketing persona named [persona] representing [segment]. Describe demographics,
motivations, pain points, and preferred channels.

### Rapid Prompt 28 — Customer Journey Map

Outline a customer journey for [product/service] from awareness to advocacy. Highlight touchpoints,
emotions, and opportunities to improve.

### Rapid Prompt 29 — Localization Strategy

Propose a localization strategy for entering [country/region]. Address content adaptation, cultural nuances,
legal requirements, and marketing channels.

### Rapid Prompt 30 — Talk Show Outline

Outline the structure for a [type of show] featuring [guest/topic]. List segments, questions, and audience
interaction elements.

### Rapid Prompt 31 — Error Handling

Describe how to handle errors for [system/process]. Define error types, user messaging, logging, and
recovery strategies.

### Rapid Prompt 32 — Roadmap Plan

Create a roadmap for [project] over the next [time frame]. Include key milestones, deliverables, and
dependencies.

### Rapid Prompt 33 — Audience Feedback Form

Develop a feedback form for [event/product/service]. Include Likert scale questions and open comments.

### Rapid Prompt 34 — Task Prioritization

Prioritize tasks from [task list] using an importance/urgency matrix.

### Rapid Prompt 35 — Market Entry Analysis

Conduct a market entry analysis for [product] in [region]. Assess competition, customer needs, and
regulatory environment.


### Rapid Prompt 36 — Pricing Strategy

Formulate a pricing strategy for [product/service]. Consider cost structure, value perception, competitor
pricing, and demand elasticity.

### Rapid Prompt 37 — Outreach Message

Write a cold outreach message to [potential partner/investor]. Keep it concise, highlight mutual benefits,
and include a call to action.

### Rapid Prompt 38 — Explainer Video Script

Write a script for a 2-minute explainer video about [topic]. Structure it into introduction, problem, solution,
benefits, and call to action.

### Rapid Prompt 39 — Newsletter Outline

Draft an outline for a monthly newsletter for [audience]. Include regular sections, themes, and engagement
features.

### Rapid Prompt 40 — Risk Assessment

Perform a qualitative risk assessment for [project]. Identify risks, assess impact and likelihood, and propose
mitigation strategies.

### Rapid Prompt 41 — Vendor Evaluation

Create criteria to evaluate vendors for [service/supply]. Include cost, quality, reliability, and alignment with
requirements.

### Rapid Prompt 42 — Brand Tagline

Brainstorm [number] tagline options for [brand/product]. Keep them catchy, concise, and aligned with
brand values.

### Rapid Prompt 43 — Community Guidelines

Draft community guidelines for [platform/group]. Emphasize respect, inclusivity, moderation policies, and
enforcement procedures.

### Rapid Prompt 44 — Meeting Agenda

Prepare an agenda for a meeting on [topic]. Include goals, agenda items, time allocation, and expected
outcomes.


### Rapid Prompt 45 — Write Case Study

Write a case study about [business/success story]. Include problem, solution, implementation, results, and
lessons learned.

### Rapid Prompt 46 — Evaluation Survey

Design an evaluation survey for [training/event]. Include questions to measure satisfaction, learning
outcomes, and suggestions.

### Rapid Prompt 47 — Transform Tone

Transform the tone of [input text] to [tone style] while preserving the meaning.

### Rapid Prompt 48 — Create Table

Create a table summarizing [information]. Use columns for [criteria] and rows for [items].

### Rapid Prompt 49 — Brand Story

Tell the brand story of [company]. Highlight origin, mission, challenges, and impact with a narrative arc.

### Rapid Prompt 50 — Goal Progress Report

Write a progress report on achieving [goal]. Include accomplishments, roadblocks, next steps, and metrics.

### Rapid Prompt 51 — Policy Summary

Summarize a policy document on [subject] into key points and implications.

### Rapid Prompt 52 — Compliance Report

Compile a compliance report for [industry/regulation]. Outline compliance status, gaps, and
recommendations.

### Rapid Prompt 53 — Team Charter

Develop a team charter for [team]. Include purpose, goals, roles, communication protocols, and success
criteria.

### Rapid Prompt 54 — Retrospective Guide

Write a guide for running a retrospective meeting. Suggest activities, timeboxing, and follow-up actions.

### Rapid Prompt 55 — Data Collection Plan

Create a data collection plan for [study]. Define variables, instruments, timeline, and data quality checks.


### Rapid Prompt 56 — Annual Report Summary

Summarize the annual report of [organization]. Highlight financial performance, strategic initiatives, and
future outlook.

### Rapid Prompt 57 — Workflow Automation

Describe steps to automate [workflow/process] using [tool/platform]. Include triggers, actions, and
monitoring.

### Rapid Prompt 58 — Employee Recognition Program

Design an employee recognition program for [company]. Define award categories, criteria, nomination
process, and celebration methods.

### Rapid Prompt 59 — Brand Persona

Develop a brand persona that personifies [brand]. Describe characteristics, personality traits, values, and
communication style.

### Rapid Prompt 60 — Focus Group Script

Draft a script for moderating a focus group about [topic]. Include introduction, warm-up questions, core
questions, and closing.

### Rapid Prompt 61 — Awareness Campaign Plan

Plan an awareness campaign for [cause/issue]. Define objectives, target audience, key messages, channels,
and measures of success.

### Rapid Prompt 62 — Cross-Functional Alignment Plan

Design a plan to align cross-functional teams on [initiative]. Outline communication routines, shared KPIs,
and conflict resolution mechanisms.

### Rapid Prompt 63 — Business Continuity Plan

Outline a business continuity plan for [organization]. Identify critical functions, backup strategies,
communication protocols, and recovery timelines.

### Rapid Prompt 64 — Rewards & Recognition Framework

Develop a rewards and recognition framework for [organization]. Include reward types, criteria, frequency,
and fairness considerations.


### Rapid Prompt 65 — Investor Outreach Plan

Create an investor outreach plan for [startup]. Identify investor profiles, messaging strategy, pitch
materials, and follow-up actions.
