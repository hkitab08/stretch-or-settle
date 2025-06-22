# stretch-or-settle
A Machine Learning Approach to Conservative Baserunning in MLB

# ⚾ Stretch or Settle

This project analyzes MLB baserunning behavior to identify instances where a player **may have been able to stretch a single into a double** but didn’t. Using **Statcast data** and **machine learning**, we aim to flag "conservative baserunning" moments and explore what factors influence those decisions.

## 💡 Project Motivation

In baseball, split-second decisions on the basepaths can make a major impact. While much attention is given to baserunning mistakes, less is known about **missed opportunities**—times when runners play it safe. This project is an attempt to:

- Quantify "should-have-been" doubles
- Analyze trends across players, teams, and game situations
- Build a predictive model using Statcast data to estimate the probability of stretching a single into a double

## 📦 Features

- Data collection using [Statcast](https://baseballsavant.mlb.com/statcast_search) via the `pybaseball` Python package
- Feature engineering: exit velocity, launch angle, hit location, sprint speed, fielding metrics, etc.
- ML model to estimate "x2B" (expected double probability)
- Detection of conservative baserunning events
- (Optional) Video or visual validation of high-probability but unrealized doubles

## 📁 Project Structure
