# SmartScout — AI-Based Youth Football Player Analysis

Final project for the Building AI course

## Summary

SmartScout is an AI-based tool that analyzes youth football match videos and identifies the most promising players based on their game behavior, actions, and performance metrics. It helps scouts and coaches make better, faster talent decisions.

## Background

In youth football, scouting is often manual, subjective, and time-consuming. Many promising players go unnoticed due to lack of data or resources. This project aims to solve:

* Lack of objective tools for player analysis  
* Time-consuming manual review of match footage  
* Missed talent in early development stages  

As a football coach and enthusiast working with clubs like [Rīgas Futbola Skola (RFS)](https://fkrfs.lv), I wanted to build a tool that supports young players in getting the recognition they deserve, while helping scouts save time and gain insights.

## How is it used?

The user (coach, scout, analyst) uploads a youth match video to the SmartScout system. The AI tracks each player’s movements and actions — passes, dribbles, shots — and generates a performance report with rankings and strengths.

Situations:
* Amateur or academy match environments  
* Early-stage player evaluation  
* Remote scouting and performance comparison  



## Data sources and AI methods

Data sources:
* Match footage from youth academies like [RFS U-14](https://www.youtube.com/@rfsacademy3152)  
* Open datasets such as [SoccerNet](https://www.soccer-net.org/)  
* Publicly available football videos (e.g., YouTube)

AI methods:
* Object tracking and player recognition using YOLOv8  
* Neural networks (CNNs, RNNs) to analyze player behavior  
* Clustering to identify top performers  
* Visualization using matplotlib and custom dashboards  

| Component      | Description                     |
|----------------|---------------------------------|
| Video Tracker  | Identifies and tracks players   |
| Action Parser  | Detects key in-game events      |
| Scoring Engine | Ranks players by performance    |

## Challenges

* Video quality and camera angles can vary significantly  
* Lack of labeled youth-level training data  
* Ethical concerns in analyzing and profiling minors  
* Generalization to different play styles and age groups  

## What next?

* Build a simple web interface for easy uploads and reports  
* Integrate more advanced metrics like positional heatmaps  
* Expand dataset through collaboration with local clubs like [RFS](https://fkrfs.lv)  
* Explore edge deployment (on tablets or phones) for live use  

Skills needed:
* Advanced computer vision techniques  
* Web and UI development  
* Real-time video processing  
* Ethics and data privacy compliance  

## Acknowledgments

* Inspired by the open-source [SoccerNet](https://www.soccer-net.org/) project  
* Concept influenced by practical coaching experience with [Rīgas Futbola Skola (RFS)](https://fkrfs.lv) and their youth development program  
* Match footage and ideas inspired by official youth content from [RFS Academy YouTube](https://www.youtube.com/@rfsacademy3152) and [Riga FC Academy](https://rigafc.lv/en/academy)  


