# Hockey Skill Interactions Analysis

A Panel Data Analysis of Interactive Effects between High-Danger Shots, Rebounds, and Secondary Skills on NHL Goal Production

## Overview

This repository contains the complete analysis examining how high-danger shooting opportunities and rebound generation jointly influence goal production in professional hockey, and how secondary skills (hits, takeaways, giveaways) interact with this relationship.

## Research Question

How do high-danger shooting opportunities and rebound generation jointly influence goal production in hockey, and how do secondary skills (hits, takeaways, giveaways) interact with this relationship?

## Methodology

- **Data**: NHL player-game level data from MoneyPuck.com (2020-21 through 2024-25 seasons)
- **Approach**: Fixed-effects panel regression with robust standard errors
- **Sample**: 1,460 players across 22,117 observations
- **Key Variables**: Per-minute rates for goals, high-danger shots, rebounds, hits, takeaways, giveaways

## Key Findings

- **Rebound generation** dominates goal production (r = 0.70) over high-danger shooting (r = 0.19)
- High-danger shots and rebounds operate as **substitutes rather than complements** 
- Secondary skills show **negligible direct correlations** with goal production
- Interaction effects lose significance under robust standard error analysis

## Usage
1. Clone the repository
2. Install required R packages
3. Run scripts in numerical order 
