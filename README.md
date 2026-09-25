# Chile Work Order and Tickets Forecast

This repo predicts how many tickets and work orders will come in each week for Chile. The data used is ticket data (`ticket_full.csv`), covering the period from 26 Dec 2024 to 30 Aug 2026. The ticket model uses all entries in this data, while the work order model uses only the entries where `has_work_order = Y`.

The ticket model is in `Tickets_weekly_forecast_sarima_tuning.ipynb`, and the work order model is in `Workorders_weekly_forecast_sarima_tuning.ipynb`.

The repo is organized under `WO and Ticket Forecasting Version 2`, which has two subfolders: Chile WO Forecasting and Chile Tkt Forecasting. Each subfolder has the same four things — a Python file with the model code, the ticket data, a saved model, and a workflow document.
