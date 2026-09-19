# A/B Testing Analysis

## Test Idea

After prioritizing the features, I wanted to see how a new checkout experience could affect user behaviour.

For this, I considered a simple A/B test with two groups of users.

## Test Setup

**Control Group:** Users see the existing checkout page.

**Treatment Group:** Users see the new checkout page.

The main metric I looked at was **Checkout Conversion Rate**.

## Results

| Group | Users | Completed Orders | Conversion Rate |
|---|---:|---:|---:|
| Control | 5,000 | 600 | 12.0% |
| Treatment | 5,000 | 708 | 14.16% |

The treatment group had a higher conversion rate.

### Calculation

Control conversion:

**600 / 5,000 = 12.0%**

Treatment conversion:

**708 / 5,000 = 14.16%**

So the conversion rate increased by:

**14.16% - 12.0% = 2.16 percentage points**

The relative increase is about **18%**.

## What This Tells Us

In this example, the new checkout experience performed better than the existing one.

But I would not consider this result enough to launch the feature immediately. I would first check whether the difference is statistically significant and whether other important metrics were affected.

Some other things I would check are:

- Average Order Value
- Cart Abandonment
- Repeat Orders
- Performance for new and existing users
- Experiment duration

## Possible Product Decision

If the result is statistically significant and there are no major negative effects on other metrics, the feature can be tested with a larger group of users.

If the result is not clear, I would collect more data or make changes to the feature before testing it again.

## Note

The numbers used here are simulated numbers created for this case study. They are not taken from a real food delivery company.
