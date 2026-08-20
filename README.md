# Awesome-Construction-Estimating

Markdown
## Top Construction Estimating Software Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Construction Cost Estimation, Quantity Takeoff, BOQ/BOM, Bid Preparation, Cost Databases, CAD/BIM Takeoff & Preconstruction Analytics*  
**Last updated: August 2026**


This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Construction Estimating Software**. These tools help contractors, subcontractors, estimators, quantity surveyors, builders, engineers, and preconstruction teams measure quantities from drawings and BIM models, build estimates, manage cost databases, prepare bids, calculate labor/material/equipment costs, and analyze project profitability.


**Examples** include STACK, PlanSwift, Buildxact, ProEst, Clear Estimates, Estimator360, CostX, Bluebeam, Trimble Quest, Buildertrend, Cubit, Methvin, B2W Estimate, Trimble WinEst, Sage Estimating, HCSS HeavyBid, Cubit Estimating, and DESTINI Estimator.


Modern construction estimating increasingly combines **digital quantity takeoff, PDF measurement, CAD/BIM extraction, assemblies, cost databases, historical project data, labor productivity, subcontractor quotes, bid management, 4D/5D BIM, AI-assisted takeoff, computer vision, and predictive cost analytics**.


**Open-source emphasis**: This repository is heavily expanded with open-source projects and building blocks that can be used to build custom construction-estimating systems — including complete estimating/BOQ platforms, PDF takeoff engines, BIM quantity extraction, CAD processing, cost databases, construction ERP systems, estimating APIs, document processing, analytics, and AI-assisted estimation.


The open-source ecosystem is much smaller than the commercial estimating-software ecosystem. However, projects such as **OpenConstructionERP** and **OpenTakeoff** now provide unusually direct open-source alternatives for BOQ, cost estimation, PDF takeoff, CAD/BIM quantity extraction, and AI-assisted estimating. OpenConstructionERP describes itself as an AGPL-3.0 self-hosted construction-estimation platform with BOQ, 4D/5D, AI, CAD/BIM takeoff and cost databases, while OpenTakeoff provides an Apache-2.0 browser-based open-source quantity-takeoff engine. 


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Construction Estimating Stack](#open-source-construction-estimating-stack)
- [Construction Estimating Building Blocks](#construction-estimating-building-blocks)
- [Important Construction Estimating Concepts](#important-construction-estimating-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms


- **[STACK](https://www.stackct.com/)**  
  Cloud-based construction takeoff and estimating platform focused on digital plan takeoff, estimating, bid preparation, and collaboration.


- **[PlanSwift](https://www.planswift.com/)**  
  Desktop construction takeoff and estimating software for converting digital plans into measurable quantities, assemblies, material takeoffs, and estimates across many construction trades.


- **[Buildxact](https://www.buildxact.com/)**  
  Cloud-based estimating and construction-management platform for builders and remodelers with digital takeoff, estimating, quoting, job costing, and project-management capabilities.


- **[ProEst](https://proest.com/)**  
  Cloud construction estimating platform supporting quantity takeoff, cost databases, assemblies, bid preparation, reporting, and integration with construction-management workflows.


- **[Clear Estimates](https://www.clearestimates.com/)**  
  Residential construction estimating platform providing pre-built cost databases, project estimates, pricing, and proposal generation.


- **[Estimator360](https://www.estimator360.com/)**  
  Construction estimating and takeoff platform focused on quantity measurement, estimating, assemblies, pricing, proposals, and project workflows.


- **[CostX](https://www.exactal.com/)**  
  Construction estimating and quantity-surveying platform from Exactal supporting 2D/3D/BIM takeoff, estimating, cost planning, and reporting.


- **[Bluebeam](https://www.bluebeam.com/)**  
  PDF-based construction documentation and measurement platform widely used for digital takeoff, markup, measurement, drawing comparison, and collaboration.


- **[Trimble Quest](https://www.trimble.com/)**  
  Trimble construction estimating and preconstruction technology ecosystem supporting estimating, takeoff, cost management, and construction workflows.


- **[Buildertrend](https://buildertrend.com/)**  
  Cloud construction-management platform with estimating, proposals, budgets, selections, scheduling, customer management, and project financial workflows.
Recommended Open-Source Combinations

Basic Open-Source Estimating

OpenConstructionERP + PostgreSQL + Grafana

Useful for BOQ, cost databases, estimates, markups, reporting, and estimating dashboards.

Open-Source Digital Takeoff

OpenTakeoff + PyMuPDF + OpenCV + PostgreSQL

Useful for PDF plan measurement and structured quantity collection.

BIM-Based Estimating

IfcOpenShell + Bonsai + OpenConstructionERP + PostgreSQL

Useful for extracting BIM quantities and connecting model elements to BOQ and cost items.

AI-Assisted Takeoff

OpenTakeoff + PaddleOCR + OpenCV + YOLO + LangGraph

Useful for combining drawing measurement, OCR, computer vision, and AI-driven estimating workflows.

Historical Cost Intelligence

PostgreSQL + DuckDB + Grafana + XGBoost

Useful for analyzing historical estimates and predicting future unit costs, labor productivity, and bid outcomes.

Construction AI Copilot

PostgreSQL + Qdrant + LlamaIndex + LangGraph + Ollama

Useful for querying specifications, historical estimates, cost databases, assemblies, subcontractor quotes, and estimating rules.

Full Open-Source Construction Estimating Stack

OpenConstructionERP + OpenTakeoff + IfcOpenShell + Bonsai + PyMuPDF + PaddleOCR + PostgreSQL + DuckDB + Grafana + YOLO + XGBoost + LangGraph + Ollama

This combination covers PDF takeoff, CAD/BIM takeoff, BOQ, cost databases, estimating, historical cost analytics, AI-assisted estimation, document intelligence, and bid preparation.

Construction Estimating Building Blocks
Quantity Takeoff

Digital Quantity Takeoff — Measuring construction quantities from digital drawings.

PDF Takeoff — Measuring quantities directly from PDF plans.

CAD Takeoff — Extracting quantities from CAD drawings.

BIM Takeoff — Extracting quantities from BIM models.

2D Takeoff — Measuring quantities from 2D drawings.

3D Takeoff — Measuring quantities from 3D/BIM models.

Area Takeoff — Measuring surface areas.

Length Takeoff — Measuring linear quantities.

Count Takeoff — Counting construction elements.

Volume Takeoff — Calculating volumes.

Weight Takeoff — Calculating material weights.

Linear Foot Takeoff — Measuring linear construction quantities.

Square Foot Takeoff — Measuring surface areas.

Cubic Yard Takeoff — Measuring earthwork/concrete quantities.

Waste Factor — Accounting for material waste.

Deduct Areas — Removing openings or excluded areas.

Scale Calibration — Establishing drawing measurement scale.

Drawing Measurement — Measuring geometry from plans.

Automated Takeoff — Automatically extracting quantities.

AI Takeoff — AI-assisted quantity extraction.

Computer Vision Takeoff — Vision-based drawing measurement.

One-Click Takeoff — Automated region measurement.

Symbol Recognition — Detecting drawing symbols.

Room Detection — Detecting rooms automatically.

Wall Detection — Detecting walls.

Door Detection — Detecting doors.

Window Detection — Detecting windows.

Fixture Detection — Detecting construction fixtures.

Sheet Classification — Identifying drawing types.

Drawing Set Management — Managing plan sets.

Drawing Revision Comparison — Comparing drawing versions.

Cost Estimating

Construction Cost Estimating — Calculating expected project cost.

Conceptual Estimating — Early-stage cost estimation.

Preliminary Estimating — Early project cost planning.

Detailed Estimating — Detailed project cost calculation.

Bid Estimating — Preparing contractor bids.

Hard Cost Estimating — Estimating direct construction costs.

Soft Cost Estimating — Estimating design, permitting, financing, and other indirect costs.

Unit Cost Estimating — Estimating based on cost per unit.

Assembly Estimating — Estimating using reusable assemblies.

Parametric Estimating — Estimating from project parameters.

Historical Estimating — Using previous projects.

Analogous Estimating — Estimating from comparable projects.

Bottom-Up Estimating — Building an estimate from detailed components.

Top-Down Estimating — Starting from overall project-level costs.

Quantity-Based Estimating — Costing based on measured quantities.

Resource-Based Estimating — Costing labor, material, and equipment resources.

Production-Based Estimating — Estimating using production rates.

Productivity-Based Estimating — Using labor productivity assumptions.

Location-Based Estimating — Adjusting prices by geography.

Market-Based Estimating — Incorporating current market conditions.

AI Estimating — AI-assisted cost estimation.

Predictive Estimating — Machine-learning-based cost forecasting.

Probabilistic Estimating — Estimating using probability distributions.

Monte Carlo Estimating — Simulation-based cost estimation.

BOQ / Cost Breakdown

Bill of Quantities (BOQ) — Structured list of construction quantities and costs.

Bill of Materials (BOM) — List of materials required.

Cost Breakdown Structure (CBS) — Hierarchical project cost structure.

Work Breakdown Structure (WBS) — Hierarchical project work structure.

Cost Code — Identifier for a cost category.

Cost Item — Individual priced construction item.

Assembly — Reusable collection of resources.

Resource — Labor, material, equipment, or subcontractor input.

Unit Rate — Cost per unit of quantity.

Labor Rate — Cost per labor unit.

Material Rate — Cost per material unit.

Equipment Rate — Equipment cost per unit/time.

Subcontractor Rate — Subcontractor pricing.

Crew Rate — Cost of a labor crew.

Crew Composition — Labor resources making up a crew.

Productivity Rate — Quantity produced per labor unit.

Waste Rate — Expected material waste.

Markup — Percentage added to cost.

Overhead — Indirect business/project costs.

Contingency — Allowance for uncertainty.

Profit Margin — Target project profit.

General Conditions — Project-specific indirect costs.

Bond Cost — Bonding expense.

Insurance Cost — Insurance expense.

Tax — Applicable taxes.

Escalation — Expected future price increases.

Bid Management

Bid Preparation — Creating contractor bids.

Tender Preparation — Preparing tender submissions.

Bid Invitation — Inviting subcontractor bids.

Bid Management — Managing bids and proposals.

Bid Leveling — Comparing subcontractor bids.

Subcontractor Quotes — Collecting subcontractor pricing.

Supplier Quotes — Collecting supplier pricing.

Quote Comparison — Comparing vendor prices.

Scope Comparison — Comparing scope coverage.

Bid Coverage — Measuring coverage of required scopes.

Bid Hit Rate — Percentage of bids won.

Bid Calendar — Managing bid deadlines.

Bid Package — Group of documents and scope for a bid.

Bid Form — Standard bid submission.

Proposal Generation — Generating client proposals.

Tender Submission — Submitting bids.

Bid Revision — Updating estimates before submission.

Bid History — Historical bid database.

Cost Databases

Construction Cost Database — Database of construction costs.

Labor Cost Database — Labor pricing database.

Material Cost Database — Material pricing database.

Equipment Cost Database — Equipment rates.

Subcontractor Cost Database — Historical subcontractor pricing.

Historical Cost Database — Historical project costs.

Regional Cost Database — Location-adjusted costs.

Cost Index — Construction price index.

Price Escalation — Modeling future cost changes.

Assembly Database — Reusable construction assemblies.

Unit Price Database — Unit construction prices.

Cost Catalog — Searchable cost item catalog.

Vendor Price Database — Supplier pricing.

Market Pricing — Current market costs.

BIM / 5D

BIM Quantity Takeoff — Extracting quantities from BIM.

5D BIM — BIM integrated with construction costs.

4D BIM — BIM integrated with schedules.

BIM Cost Estimating — Costing BIM elements.

Model-Based Estimating — Estimating directly from models.

IFC Takeoff — Quantity extraction from IFC.

Revit Takeoff — Quantity extraction from Revit.

BIM Cost Mapping — Connecting model elements to cost items.

BIM-to-BOQ — Converting model quantities into BOQ.

BIM-to-Cost — Mapping BIM objects to costs.

BIM Cost Database — BIM-connected pricing.

Model Quantity Extraction — Extracting quantities automatically.

Model-Based Cost Planning — Cost planning from BIM.

5D Cost Model — Integrated model and cost structure.

Construction AI

AI Quantity Takeoff — AI-assisted measurement.

AI Cost Estimation — AI-generated estimates.

AI Cost Matching — Matching descriptions to cost items.

AI Assembly Generation — Generating assemblies.

AI Drawing Understanding — Understanding construction plans.

AI Specification Analysis — Analyzing specifications.

AI Bid Assistant — AI assistance for bids.

AI Estimator Copilot — AI assistant for estimators.

Construction RAG — Retrieval-augmented generation over construction documents.

Construction Knowledge Graph — Structured construction knowledge.

Estimating Agent — AI agent performing estimating workflows.

Agentic Takeoff — AI agents executing quantity takeoff.

AI Cost Database Search — Natural-language cost lookup.

AI Historical Estimate Search — Searching previous estimates.

AI Bid Analysis — AI-assisted bid comparison.

AI Scope Detection — Detecting scope from documents.

AI Drawing Classification — Classifying construction drawings.

AI Symbol Detection — Detecting plan symbols.

AI Room Detection — Detecting rooms.

AI Wall Detection — Detecting walls.

AI Door/Window Detection — Detecting building openings.

Construction Analytics

Estimate Analytics — Analytics of estimates.

Cost Analytics — Analysis of construction costs.

Bid Analytics — Analysis of bidding activity.

Bid-Hit Analytics — Analysis of bid success.

Cost Variance — Difference between estimated and actual cost.

Estimate Accuracy — Accuracy of estimates against actuals.

Estimate-to-Actual Analysis — Comparing estimates with project outcomes.

Historical Cost Analysis — Analyzing past costs.

Cost Benchmarking — Comparing costs.

Labor Productivity Analytics — Analyzing labor productivity.

Material Price Analytics — Tracking material prices.

Equipment Cost Analytics — Analyzing equipment costs.

Subcontractor Analytics — Analyzing subcontractor pricing.

Supplier Analytics — Analyzing supplier pricing.

Profitability Analytics — Analyzing project profitability.

Margin Analysis — Analyzing project margins.

Cost Forecasting — Predicting costs.

Price Forecasting — Predicting prices.

Risk Analytics — Quantifying estimating risks.

Estimate Benchmarking — Comparing estimates against historical projects.

Construction Document Intelligence

Drawing OCR — OCR for construction drawings.

Specification OCR — OCR for specifications.

Document Classification — Classifying construction documents.

Drawing Classification — Identifying drawing types.

Drawing Search — Searching drawing content.

Specification Search — Searching specifications.

Symbol Recognition — Recognizing plan symbols.

Text Extraction — Extracting text from construction documents.

Dimension Extraction — Extracting dimensions.

Schedule Extraction — Extracting door/window/equipment schedules.

Room Schedule Extraction — Extracting room data.

Material Schedule Extraction — Extracting material schedules.

Document RAG — Retrieval-augmented construction-document analysis.

Important Construction Estimating Concepts

Quantity Takeoff

Digital Takeoff

Automated Takeoff

AI Takeoff

PDF Takeoff

CAD Takeoff

BIM Takeoff

2D Takeoff

3D Takeoff

5D BIM

Bill of Quantities

Bill of Materials

Cost Database

Unit Cost

Unit Rate

Assembly

Resource Cost

Labor Cost

Material Cost

Equipment Cost

Subcontractor Cost

Direct Cost

Indirect Cost

General Conditions

Overhead

Contingency

Profit

Markup

Production Rate

Labor Productivity

Crew Productivity

Material Waste

Cost Code

Cost Breakdown Structure

Work Breakdown Structure

Historical Cost

Historical Estimate

Conceptual Estimate

Preliminary Estimate

Detailed Estimate

Bid Estimate

Parametric Estimate

Analogous Estimate

Bottom-Up Estimate

Top-Down Estimate

Probabilistic Estimate

Monte Carlo Cost Estimate

Construction Cost Index

Price Escalation

Location Factor

Market Adjustment

Cost Benchmarking

Estimate Accuracy

Estimate-to-Actual

Cost Variance

Bid-Hit Rate

Bid Leveling

Subcontractor Quote

Supplier Quote

Quote Comparison

Bid Package

Tender Package

Scope of Work

Scope Gap

Scope Coverage

Bid Calendar

Bid Management

Proposal Generation

Tender Submission

Cost Planning

Cost Control

Cost Forecasting

Construction Cost Analytics

Construction Data Analytics

Historical Cost Analytics

Labor Productivity Analytics

Subcontractor Analytics

Material Price Analytics

AI Cost Estimation

AI Quantity Takeoff

AI Drawing Analysis

AI Specification Analysis

AI Bid Analysis

AI Cost Matching

AI Estimator Copilot

Estimating Agent

Agentic Takeoff

Construction RAG

Construction Knowledge Graph

Construction Document Intelligence

Computer Vision Takeoff

Drawing Recognition

Symbol Recognition

Room Detection

Wall Detection

Door Detection

Window Detection

Fixture Detection

Dimension Detection

OCR

Construction OCR

Drawing OCR

Specification OCR

BIM Cost Estimating

Model-Based Estimating

BIM-to-BOQ

BIM-to-Cost

IFC Quantity Takeoff

Revit Quantity Takeoff

CAD Quantity Extraction

DWG Takeoff

DXF Takeoff

Point Cloud Takeoff

Scan-to-BIM

Scan-to-Cost

Digital Construction

Construction Digital Twin

5D Digital Twin

Preconstruction Technology

Construction Technology

Construction AI

Construction Automation

Construction Data Platform

Construction Estimating API

Estimating-as-a-Service

Cost Data API

Construction Cost Intelligence

Construction Market Intelligence

Construction Pricing Intelligence

Construction Procurement Intelligence

Construction Bid Intelligence

Construction Profitability Intelligence

Preconstruction Intelligence

Contractor Intelligence

Estimator Copilot

Quantity Surveyor Copilot

Preconstruction Copilot

Construction Cost Copilot

Autonomous Estimating

Autonomous Takeoff

AI-Native Estimating

Open-Source Estimating

Open-Source Takeoff

Open BIM Estimating

Open Construction Data

Open Construction Cost Database

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow the existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/hosted or open-source.

For open-source projects, identify the primary capability — estimating, quantity takeoff, BIM, CAD, OCR, computer vision, cost databases, ERP, analytics, or AI.

Clearly distinguish open-source, source-available, open-core, research projects, student projects, and commercial hosted products.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Do not describe a generic CAD, BIM, OCR, ERP, database, or AI framework as a complete construction-estimating platform unless it actually provides estimating functionality.

Do not describe a generic project-management platform as estimating software merely because it contains budgets or financial features.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Commercial construction-estimating platforms frequently combine software with proprietary cost databases, construction-price data, drawing-processing technology, BIM integrations, and project-management systems.

The open-source ecosystem is considerably more fragmented than the commercial construction-estimating market.

Some open-source projects are complete applications, while others are libraries, frameworks, research projects, or building blocks for constructing a custom estimating platform.

Always verify the current license, maintenance status, documentation, dependencies, and security posture before deploying an open-source project.

Cost databases and pricing information can vary significantly by geography, trade, labor market, project type, and date. Do not assume that a free/open database provides commercially reliable current pricing.

AI-generated quantities, classifications, unit costs, and estimates should always be reviewed by a qualified estimator before being used for contractual bids, tenders, procurement, or financial commitments.

BIM-derived quantities can contain modeling errors, omissions, duplicated elements, or classification problems and should be independently validated.

Construction estimates should account for project-specific scope, specifications, drawings, site conditions, labor productivity, material availability, equipment, subcontractor pricing, taxes, escalation, contingency, insurance, bonds, overhead, and profit.

Open-source software connected to project financial systems, estimating databases, cloud storage, or construction-management platforms should use appropriate authentication, authorization, backups, audit logging, and security controls.

Made for general contractors, subcontractors, estimators, quantity surveyors, builders, construction managers, civil contractors, MEP contractors, architects, engineers, BIM professionals, preconstruction teams, developers, construction-tech researchers, and developers.
Let's make construction estimating more open, data-driven, automated, accurate, interoperable, intelligent, and accessible.
