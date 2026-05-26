# Salmon Bank PH — Experiment prototypes

Working prototypes and landing page tests for Salmon Bank Philippines (salmon.ph).

## Contents

### Salmon / Interest Rate LP

A 4-step quiz landing page prototype for the deposit acquisition experiment (Experiment 1, Variant B). Designed to be A/B tested against the existing flat deposit landing page at https://salmon.ph/salmonbank-deposits.

**Live preview:** https://stitov2896.github.io/salmon/Salmon/Interest%20Rate%20LP/

**Flow:**
1. Amount (slider + input, default ₱10,000)
2. Term (6 months to 5 years)
3. Outcome (concrete peso projection + comparison to traditional savings)
4. Lead form (name + phone)
5. Confirmation + Salmon App download CTA

**Built with:** static HTML/CSS/JS, no build step, no dependencies. Uses Salmon's actual Gilroy font and brand colours (#F05A5A primary).

**Rate logic implemented per Salmon's published ladder:**
- ₱5,000 to ₱499,999 → 6.00% p.a. all terms
- ₱500,000 to ₱999,999 → 6.50% p.a. for 12-month+ terms
- ₱1,000,000 to ₱50,000,000 → 8.00% p.a. for 12-month+ terms

## Notes

This is a prototype repository for design review and stakeholder presentation. It is not production code and is not connected to Salmon Bank's actual backend systems. Form submissions log to the browser console only.
