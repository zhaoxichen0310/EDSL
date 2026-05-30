# EDSL Project

This repository contains my MACS 30755 EDSL synthetic survey replication project.

## Overview

This project compares Pew Research Center’s human survey results with AI-generated survey responses.

The survey question asks how people feel about the increased use of artificial intelligence in daily life:

* More excited than concerned
* More concerned than excited
* Equally concerned and excited
* No answer

## Files

* `edsl_survey.ipynb`: main code notebook
* `ai_responses.json`: AI survey responses
* `fig1_overall.png`: overall comparison figure
* `fig2_by_age.png`: comparison by age
* `fig3_by_gender.png`: comparison by gender
* `fig4_by_edu.png`: comparison by education
* `fig5_tvd.png`: Total Variation Distance figure

## Method

I used EDSL to create 72 AI agents with demographic traits, including age group, gender, education level, and country. Each agent answered the same Pew survey question once.

## Main Finding

The AI agents showed more polarized responses than human respondents. In particular, no AI agent selected “Equally concerned and excited,” even though many human respondents chose that option.
