#DRIP Fixed Income

**v2.34**  *29 September 2016*

DRIP Fixed Income is a collection of Java libraries for Instrument/Trading Conventions, Treasury Futures/Options, Funding/Forward/Overnight Curves, Multi-Curve Construction/Valuation, Collateral Valuation and XVA Metric Generation, Calibration and Hedge Attributions, Statistical Curve Construction, Bond RV Metrics, Stochastic Evolution and Option Pricing, Interest Rate Dynamics and Option Pricing, LMM Extensions/Calibrations/Greeks, Algorithmic Differentiation, Asset Backed Models and Analytics, .

DRIP Fixed Income is composed of the following main libraries:
 * Instrument/Trading Conventions Library
 * Treasury Futures/Options Library
 * Funding/Forward/Overnight Curve Library
 * Multi-Curve Construction/Valuation Library
 * Collateral and XVA Metrics Library
 * Position Horizon Analyzer Library
 * Statistical Curve Construction Library
 * Bond RV Metrics Library
 * Stochastic Evolution and Option Pricing Library
 * Interest Dynamics and Option Pricing Library
 * LMM Extensions, Calibration, and Greeks Library
 * Algorithmic Differentiation Library
 * Asset Backed Model Library

For Installation, Documentation and Samples, and the associated supporting Numerical Libraries please check out [DRIP] (https://github.com/lakshmiDRIP/DRIP).


##Features

###Instrument/Trading Conventions Library

####Associations and Exchanges
 * Associations
 * Exchanges

####Date Conventions
 * Day Count Conventions
 * Business Day Conventions

####Overnight and IBOR-like Indexes
 * IBOR Indexes - Introduction
 * Main IBOR Indices
 * Other IBOR Indices
 * Overnight Index Definitions
 * Overnight Index Committees and Meeting Dates

####Over the Counter Instruments
 * Forward Rate Agreement
 * Interest Rate Swaps
 * Vanilla IRS
 * Interest Rate Swaps (Basis Swaps: IBORfor IBOR)
 * Cross Currency Swaps (IBOR for IBOR)
 * Constant Maturity Swaps
 * Swap Indexes
 * Overnight Indexed Swaps
 * Swap Option
 * Forex and Forward Swaps

####Exchange Traded Instruments
 * Overnight Futures
 * Short-Term Interest Rate Futures (STIR Futures)
 * Currency Specific Futures
 * Interest Rate Futures Option - Premium
 * Interest Rate Futures Option - Margin
 * Bank Bill Futures - AUD Style
 * Deliverable Swap (IRS) Futures (PV Quoted)
 * Bond Futures (non AUD/NZD)
 * Country Specific Bond Futures - USD
 * Country Specific Bond Futures - Germany
 * Country Specific Bond Futures - Spain
 * Country Specific Bond Futures - UK
 * Country Specific Bond Futures - Japan
 * Options on Bond Futures (non AUD/NZD) - Premium
 * Options on Bond Futures (non AUD/NZD) - Margin
 * AUD-NZD Bond Futures

###Treasury Futures/Options Library
####Treasury Futures Trading and Hedging
 * Contract Detail Specifications

####Identification of the CTD in the Basket
 * The Conversion Factor
 * Old vs. Active Treasury
 * Market Parameters Influencing the CTD Calculation
 * Impact of Yield Curve Changes

####Valuation of Treasury Futures Contract
 * Futures Contract and Mark-To-Market
 * Role of the Clearing Corporation
 * Delivery Options for the Underlying
 * Implied Basis for the Futures
 * Net Basis For Treasury Futures

###Funding/Forward/Overnight Curve Library

####Curve Builder Features
 * Discount Curves

####Curve Construction Methodology
 * Approach
 * State Span Design Components
 * Curve Calibration From Instruments/Quotes
 * Calibration Considerations

####Curve Construction Formulation
 * Segment Linear Discount Curve Calibration
 * Curve Jacobian

####Stream Based Calibration
 * Latent State Formulation Metric (LSFM)
 * Stream Inference Setup
 * Coupon Period Based Calibration Specification
 * Stream Based Calibration Specification
 * Calibration of Multi-Stream Components

####Spaning Splines
 * Setup and Formulation
 * Challenges with the Spanning Spline Approach

####Monotone Descreasing Splines
 * Exponential Rational Basis Spline
 * Exponential Mixture Basis Set

####Hagan-West (2006) Smoothness Preserving Spanning Spline
 * Monotone/Convexity Preserving Estimator
 * Positivity Preserving
 * Ameliorating Estimator
 * Harmonic Spline Extension to the Framework above
 * Minimal Quadratic Estimator

####Extrapolation in Curve Construction

####Multi-Pass Curve Construction
 * Bear-Sterns Multi-Pass Curve Building Techniques

####Transition Spline (Or Stitching Spline)
 * Stretch Modeling using Transition Splines
 * Stretch Partition/Isolation in Transition Splines
 * Knot Insertion vs. Transition Splines
 * Overlapping Stretches

####Penalizing Exact/Closeness of Fit and Curvature Penalty

####Index/Tenor Basis Swaps
 * Component Layout and Motivation
 * Formulation

####Multi-Stretch Merged Curve Construction
 * Merge Stretch Calibration

####Latent State Manifest Measure Sensitivity
 * Float-Float Manifest Measure Sensitivities
 * Multi-reset Floating Period

####OIS Valuation and Curve Construction
 * Base Framework and Environment Setup
 * OIS Valuation Extensions and Approximations
 * OIS-FX Basis Swap Valuation and Approximations
 * Arithmetic Accrual Convexity Correction
 * Composed Period Latent State Loadings

####Spline Based Credit Curve Calibration

###Multi-Curve Construction/Valuation Library

####Correlated Multi-Curve Build-out
 * Standard FRA Setup
 * Standard FRA Options
 * No arbitrage and Counter-party Risk Based Standard FRA Formulation
 * Market FRA Setup
 * Futures
 * Multi-Curve Swap Valuation

####Cross Currency Basis Swap
 * Product Details and Valuation
 * Building the CCS Discount Curve
 * Custom CCBS Based Curve Construction SKU
 * Mark-To-Market Cross-Currency Swap Valuation
 * Mark-To-Market Cross-Currency Swap - Valuation Formulation
 * Absolute/Relative MTM Application
 * Per-Trade Risk Isolation Components

###Collateral and XVA Metrics Library

####Collateral Agreements and Derivatives Valuation
 * Two Collateralized Assets
 * Setup pf the Collateral Curve Dynamics
 * Collateralized Black-Scholes Formulation
 * Collateralization and Funding Derivative Valuation
 * Collateral PDE Formulation
 * Formward Contract Valuation
 * European Style Options
 * Cross-Currency Model
 * Collateral Choice Model

####CVA and Funding Adjustments PDE
 * Counterparty Risk and Funding Costs
 * Notation, Symbology, and Key PDE's
 * Model Setup and the Derivation of the Bilateral Risky PDE
 * Using VHat (T, S) and Mark-To-Market at Default
 * Using V (T, S) and Mark-To-Market at Default
 * Funding and Default Payoff Examples
 * Counter-party Funding and PDE Extensions
 * Balance Sheet and Funding Cost Management
 * Unified Framework for Bilateral Counterpart Risk and Funding Adjustments
 * Simple Model for the Impact of Derivative Asset on Balance Sheet and Funding
 * Balance Sheet Management to Mitigate Funding Costs
 * Funding Strategies and Costs Impact
 * Generalized Semi-replication and Pricing PDE
 * Semi-replication
 * Examples of Different Bond Portfolios
 * The Perfect Replication - FCA Vanishes
 * Semi-replication with no Shortfall at own Default
 * Set-offs
 * Semi-replication with a Single Bond
 * Burgard and Kjaer (2013) Case Study

####Accounting for OTC Derivatives: Funding Adjustments and Re-hypothecation Option
 * Status of Currenct FCA/FBA Accounting
 * Comaprison between FCA/FBA and FVA/FDA
 * OTC vs. Repo Markets
 * Modus Operandi of Funding Desks
 * MTM and the Asset Liability Symmetry
 * Rigorous Framework for Funding Costs
 * Funding Set VM RHO Computation
 * Shortcomings of Traditional CVA Systems
 * Addressing the Shortcomings of FCA/FBA Accounting
 * Valuation Adjustment Estimation Framework Setup
 * OTC Bookds Funding Set Decomposition
 * Inconsistent Booking under the FCA/FBA
 * Improvements Offered by the FVA/FDA Accounting
 * CET1 Deductions
 * "Going Concern" or Defaulable Banks
 * Cash Flow Streams Categorization
 * Accounting Rules
 * Contra-Asset and Contra-Liability Accounting for Credit Risk
 * Contra-Asset and Contra-Liability Accounting for Funding
 * Accounting Cash Flow Setup Framework
 * Cash Flows related to VM Funding
 * Cash Flows at Counter-party Default
 * Cash Flows at Bank Default
 * CVA and DVA
 * FVA and FDA
 * FCA and FBA
 * CA and CL Adjustments
 * Own Credit Sensitivities
 * Triggers and Close-out Adjustments
 * Collateral Triggers and Close-outs
 * Incorporating ISDA 1992 Close-outs
 * VM Re-hypothecability across Funding Sets
 * Trade and Portfolio FTP Estimation
 * FTP for FCA/FBA Accounting
 * FTP for FVA/FDA Accounting
 * Exit Prices and Fair Valuation
 * FVA/FDA Accounting
 * FCA/FBA Accounting
 * Liquidity Spreads, Asset Liability Symmetry, and Alternative Allocations for Excess Collateral
 * Working Capital Management and Operations
 * Equity Gain and Debt Gain
 * Liquidity Based Analysis and Treatment
 * Problems with Gain Accounting
 * Albanese and Andersen (2014) Case Study
 * Case Study Setting and Purpose
 * Scenario Estimation of the XVA Metrics
 * Product and Scenario Threshold Type Scenarios
 * XVA Error Metrics and Incrementals
 * Estimation ofthe FCA/FBA - FVA/FDA Mismatch
 * Traditional Challenges with Derivative Accounting
 * Problems with FCA/FBA Accounting
 * FVA/FDA vs. FCA/FBA Enhancement
 * Trading Staff Point of View
 * Challenges with the XVA Metric Estimation
 * Shortfalls of the FVA/FDA Scheme
 * Alternate Specialized Value Metrics

###Position Horizon Analyzer Library

###Statistical Curve Construction Library

###Bond RV Metrics Library

###Stochastic Evolution and Option Pricing Library

###Interest Dynamics and Option Pricing Library

###LMM Extensions, Calibration, and Greeks Library

###Algorithmic Differentiation Library

###Asset Backed Model Library


##Contact

lakshmi@synergicdesign.com
