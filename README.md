Chile Work Order and Tickets Forecast

This repo has the work order and ticket forecasting models for Chile.

Data used: ticket data (ticket_full.csv)

Ticket model: all entries
Work order model: only entries where has_work_order = Y

Duration: 26 Dec 2024 to 30 Aug 2026

Model: SARIMA + GLM ensemble (75% GLM, 25% SARIMA), forecasts weekly volume

Result: 12.64% weekly MAPE on the holdout weeks

Notebooks: Tickets_weekly_forecast_sarima_tuning.ipynb and Workorders_weekly_forecast_sarima_tuning.ipynb
