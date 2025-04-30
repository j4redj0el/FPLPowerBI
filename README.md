# Using PowerBI to make Fantasy Premier League (FPL) Decisions 

## Introduction 
Fantasy Premier League is an online game in which players collect points based on how real-life footballers perform each week. Simply put: you choose a virtual team of Premier League footballers, and if their real-life counterparts do well, you get points. 

If you have Erling Haaland in your FPL team and he scores a goal for Manchester City, you will earn points. Simple, right? Similarly, if you have Jordan Pickford as your goalkeeper and he keeps a clean sheet, you will be rewarded. (explanation from fourfourtwo.com) 

## Aim of Project 
This project uses Power BI to help FPL managers (players) select the best players for their teams. The Power BI file in this repository contains three dashboards designed to support decision-making and optimize player selection.

## Dashboards 

### Player Comparison Table 

PL managers often face challenges when choosing between players. The dashboard below features a player comparison table that allows users to compare two players based on real-season statistics, FPL metrics, and expected statistics (xG and xA etc). Users can search for specific players to assess and compare them side by side.

![cover](https://github.com/j4redj0el/FPLPowerBI/blob/main/Player_comparison_tableFPL.jpg)

### Player Identifer 

This dashboard helps players to identify players by ranking, based on specfic statistics (Expected Goals, Expected Assists, Form etc). Each row represents a different position. This allows managers (players) to identify different players for selection based on their own personal game strategy strategy. 

![cover](https://github.com/j4redj0el/FPLPowerBI/blob/main/FPLPlayer_identifier.jpg)

### Value-for-Money 

This dashboard shows the Value for Money (VFM) of players, which is calculated by dividing the total points earned by a player's price (in £m). The larger bubbles in the scatter plot represent players who provide the best value for money, meaning they have a high number of points for a relatively low price. The plot compares Total Points (on the y-axis) and Price (£m) (on the x-axis), with the size of the bubbles reflecting the Value for Money score, so players with higher VFM appear larger and easier to spot. This allows managers (players) to optimise their selections, identifying players that give the best Return on Investment. This is key, as saving funds allows room to invest in higher-quality squad players.

The dashboard allows the user to filter based on position and team and the output will show the best 'Value for Money' Player based on their selection. 

For example, the image below shows the Most 'Value-for-money' forward from within Arsenal, Chelsea, Liverpool, Man City and Spurs. This just not mean the player produces the most points, but rather a good return on investment given the player's Price amount. 

![cover](https://github.com/j4redj0el/FPLPowerBI/blob/main/FPLValue_for_money.jpg)
