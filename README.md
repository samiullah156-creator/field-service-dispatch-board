# FieldDesk: Field Service Dispatch Board

**A dispatch board for an HVAC and home services team with a live technician map, the daily schedule and unassigned jobs in one view.**

![Home Services](https://img.shields.io/badge/Home%20Services-167dfe?style=flat-square) ![Dispatch and technician dashboard](https://img.shields.io/badge/Dispatch%20and%20technician%20dashboard-9533fa?style=flat-square) ![React](https://img.shields.io/badge/React-231f20?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-231f20?style=flat-square) ![Python](https://img.shields.io/badge/Python-231f20?style=flat-square) ![Maps API](https://img.shields.io/badge/Maps%20API-231f20?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-231f20?style=flat-square) ![Supabase](https://img.shields.io/badge/Supabase-231f20?style=flat-square)

![FieldDesk dispatch board: live technician map, jobs today, completed jobs, average ticket, first-time fix rate and technician schedule.](assets/cover.webp)

## Overview

Dispatchers and owners were tracking jobs and technician performance in spreadsheets and phone calls. Lexvaxa built FieldDesk, a custom dashboard for an HVAC and home services company. It shows a live map of technicians on the road, each technician's schedule for the day, unassigned jobs, and the numbers that matter: jobs booked and completed, average ticket and first-time fix rate, plus jobs per week, by technician and by job type. Screens shown use sample data, so no client records are exposed.

## The challenge

Jobs, routes and technician performance were managed by phone and spreadsheet, so the office had no clear picture of the day.

## The solution

A React dispatch board connected to the field service system and Maps API, with a live map, schedule lanes and performance metrics.

## Key features

- Live map of technicians on the road
- Technician schedule lanes with job status
- Unassigned job alerts with distance
- Jobs booked, completed and average ticket
- First-time fix rate
- Jobs per week, by technician and by job type

## Results

- Dispatch, jobs and technician performance visible in one place

## Tech stack

React · Node.js · Python · Maps API · n8n · Supabase

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/field-service-dispatch-board
- Built by **Ch Muhammad Samiullah** ([GitHub](https://github.com/samiullah156-creator)) at [Lexvaxa](https://lexvaxa.com)
