Chile Work Order and Tickets Forecast

This repo predicts how many tickets and work orders will come in each week for Chile.

Data used: ticket data (ticket_full.csv)

Ticket model: uses all entries
Work order model: uses only entries where has_work_order = Y

Duration: 26 Dec 2024 to 30 Aug 2026

Model: SARIMA + GLM ensemble (75% GLM, 25% SARIMA) — forecasts weekly volume

Result: 12.64% weekly MAPE (average forecast error) on unseen weeks

Notebooks:

Tickets_weekly_forecast_sarima_tuning.ipynb — tickets
Workorders_weekly_forecast_sarima_tuning.ipynb — work orders
