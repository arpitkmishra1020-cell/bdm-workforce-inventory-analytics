# Data Dictionary

## Public-data policy

The public repository does **not** contain the original business
records. Financial series are indexed so the six-month mean equals 100,
inventory item names are replaced with anonymised category IDs, and
workforce/service data are provided as aggregate summaries.

## Files

### `monthly_procurement_credit_indexed.csv`

  -----------------------------------------------------------------------
  Field                               Meaning
  ----------------------------------- -----------------------------------
  `month`                             Month in the Jan-Jun 2026 study
                                      period

  `procurement_index`                 Monthly procurement expenditure
                                      divided by the six-month mean × 100

  `credit_transaction_index`          Monthly credit transaction value
                                      divided by the six-month mean × 100
  -----------------------------------------------------------------------

### `inventory_abc_anonymized.csv`

  -----------------------------------------------------------------------
  Field                               Meaning
  ----------------------------------- -----------------------------------
  `category_id`                       Anonymised inventory category
                                      identifier

  `value_share_pct`                   Category contribution to classified
                                      inventory value

  `cumulative_value_pct`              Cumulative inventory-value
                                      contribution

  `abc_class`                         ABC classification based on
                                      cumulative value

  `inventory_value_index`             Category inventory value divided by
                                      total classified inventory value ×
                                      100
  -----------------------------------------------------------------------

### `workforce_sla_aggregate.csv`

  Field                  Meaning
  ---------------------- ---------------------------------------------------
  `attendance_status`    Workforce attendance category
  `sla_met`              Number of service visits meeting SLA
  `sla_breached`         Number of service visits breaching SLA
  `service_visits`       Total service visits associated with the category
  `sla_compliance_pct`   SLA-met visits / total visits × 100

### `service_quality_summary.csv`

  Field      Meaning
  ---------- ----------------------------
  `metric`   Service-quality indicator
  `value`    Reported value
  `unit`     Percentage or rating scale
