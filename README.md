# F1 Bahrain GP in Malaysia 2026: Power BI Dashboard

Formula 1 returned to PETRONAS Sepang International Circuit after 9 years. This project turns the 2026 Bahrain Grand Prix in Malaysia into an interactive Microsoft Power BI dashboard, built from official race timing data.

Link access to Microsoft Power BI dashboard: [F1 Bahrain 2026 Power BI Dashbord](https://app.powerbi.com/view?r=eyJrIjoiNzZhNzBjNjAtYzNjNy00Mjg4LTk5OWUtOWU2MDRlN2QxMTlkIiwidCI6IjBlMGRiMmFkLWM0MTYtNDdjNy04OGVjLWNlYWM0ZWU3Njc2NyIsImMiOjEwfQ%3D%3D)

![Alternative text description](https://github.com/herr-hollis/F1-Bahrain-2026-Power-BI/blob/f2dad356e33c95d00f8250dabb31748facf608a9/F1%20Bahrain%20Grand%20Prix%202026%20Power%20BI%20Final.png)
## Report pages

| Page | What it shows |
|---|---|
| Race Overview | Lap-by-lap positions, podium, positions gained or lost, race control events |
| Pace & Tyre Strategy | Tyre stints, lap-time distribution, fuel-corrected tyre degradation |
| Telemetry Duel | Compare any two drivers: speed, throttle, braking, track dominance by sector |
| Sepang Then vs Now | 2017 Malaysian GP vs 2026 on the same circuit |
| Team Radio | Radio clips transcribed with OpenAI Whisper, word clouds per driver |

## Tools

- **Python**: FastF1, Jolpica-F1 and OpenF1 APIs for data collection and cleaning
- **Jupyter Notebook** (Anaconda Navigator): data pipeline
- **Google Colab** (NVIDIA T4 GPU): Whisper transcription of team radio
- **Microsoft Excel**: data checks and validation
- **Power BI with DAX**: data model, measures and visuals

The data is a **snapshot** of the 2026 Sepang race weekend. It does not update automatically, because the race data is final.

## Data sources

- [FastF1](https://github.com/theOehrly/Fast-F1): timing, telemetry and weather
- [Jolpica-F1](https://github.com/jolpica/jolpica-f1): standings and historical results
- [OpenF1](https://openf1.org): sessions and team radio

## Disclaimer

This is an unofficial fan project. It is not affiliated with Formula 1, the FIA or any team.

## Author

**Hollis Francis** · BSc MSc Physics
GitHub: [@herr-hollis](https://github.com/herr-hollis)
