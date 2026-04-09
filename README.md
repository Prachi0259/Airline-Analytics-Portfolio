# Airline Analytics Portfolio | MySQL · SQL 

SQL-based analysis of 51,582 US domestic flights, uncovering delay patterns, route performance, and airline rankings across 14 carriers and 319 airports.

---

## Links

[LinkedIn](https://www.linkedin.com/in/prachi252/) · [GitHub](https://github.com/Prachi0259)

---

## About

This project analyses the 2015 US Domestic Flights Dataset using MySQL — exploring airline performance, delay trends, busiest routes, and worst-performing airports through 7 SQL queries ranging from basic aggregations to CTEs and Window Functions.

**Source:** Kaggle — 2015 Flight Delays and Cancellations

---

## Dataset

| File | Description | Rows |
|------|-------------|------|
| flights.csv | Flight records with delay, distance, time info | 51,582 |
| airlines.csv | Airline IATA codes and names | 14 |
| airports.csv | Airport codes, cities, states, coordinates | 319 |
| cancellation_codes.csv | Cancellation reason codes | 4 |

---

## Key Findings

Virgin America has the best on-time rate at 63.9% despite flying the longest average routes (1,485 miles), while Frontier Airlines is the worst performer at 30.46 min average arrival delay, a 37x performance gap.

JFK to LAX is the busiest US domestic route, with LAX appearing in 6 of the top 10 busiest corridors.

Friday is the worst day to fly (9.84 min avg delay), and Saturday is the best (5.46 min avg delay). DFW Dallas is the worst departure airport at 32.62 min avg delay, with Houston placing two airports, HOU and IAH, in the top 10 worst.

---

## SQL Techniques

| Query | Technique |
|-------|-----------|
| Flights per airline | JOIN, GROUP BY, ORDER BY |
| Avg delay per airline | AVG(), ROUND() |
| Busiest routes | Double JOIN on same table |
| Delays by day | CASE WHEN |
| Worst airports | HAVING clause |
| Airline scorecard | Multiple aggregations |
| Performance ranking | CTE + RANK() Window Function |

---

## Repository Structure

```
airline-analytics/
├── data/
│   ├── airlines.csv
│   ├── airports.csv
│   ├── cancellation_codes.csv
│   └── flights.csv
├── queries/
│   ├── 01_flights_per_airline.sql
│   ├── 02_avg_delay_per_airline.sql
│   ├── 03_busiest_routes.sql
│   ├── 04_delays_by_day.sql
│   ├── 05_worst_airports.sql
│   ├── 06_airline_scorecard.sql
│   └── 07_performance_ranking_cte.sql
├── dashboard/
│   └── airline_analytics_portfolio.html
└── README.md
```

---

## Tools

MySQL Workbench · SQL (JOINs, CTEs, Window Functions)  · Google Colab

---

## Author

**Prachi**
prachi7.work@gmail.com · [LinkedIn](https://www.linkedin.com/in/prachi252/) · [GitHub](https://github.com/Prachi0259)
