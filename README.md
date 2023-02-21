# SRFCobjective
code and data for SRFC escapement objective analysis

Code and data to accompany "An approach to defining a Sacramento River Fall Chinook escapement objective considering natural production, hatcheries, and risk tolerance" by William H. Satterthwaite

The coefficients for Equation 2 are fitted in UpperSacSRbasedObjective/UpperSacSR.r

The coefficients for Equations 3 and 4 are from Munsch et al. 2020, with further details on the flow covariate derivation and z-score transformation contained in MunschEtAlModel/Re_ a couple requests related to 2020 CJFAS paper.rtf

Figure 1 is produced by Fig1plotter/MakeFig1.r

Figure 2 is produced by HatcheryGoalModel/HatcheryGoalModel.r. Although not presented in the main text, HatcheryGoalModel-LongTimeFrame contains a sensitivity analysis fitting the same model to data from 1970-2021 instead of 2002-2021. While this larger dataset offers some statistical advantages (e.g., increased power and ability to estimate confidence intervals), the earlier data may not be representative due to changes in flow regimes, hatchery practices, and offsite releases which will all tend to change how spawners are distributed across the landscape.

Figure 3a is produced by UpperSacSRbasedObjective/UpperSacSR.r and Figure 3b is produced by WholeBasinSRobjective/Munsch_objective_mapper.r

Figure 4a is produced by UpperSacSRbasedObjective/UpperSacSR.r and Figure 4b is produced by WholeBasinSRobjective/Munsch_objective_mapper.r

Figure 5 is produced by OutcomeError/QuantifyOutcomeError.r. Note that the preseason expectations were copied by hand from the annual "preseason-report-iii" documents in "EscapementPrediction-Datasources". While error-checking was performed, other users of these numbers are encouraged to do their own cross-checking between the Excel file and source documents. Please notify will.satterthwaite@noaa.gov if any errors are found. Note also that the 2021 postseason escapement estimate was considered preliminary at the time of the analysis and may be revised slightly in the future, users should check the latest version of the Preseason Report 1 available from https://www.pcouncil.org/managed_fishery/salmon/ (similarly new Preseason Report III documents from that site can provide preseason expectations for additional years once available).

Table A1 is produced by EscapementComposition/SacramentoEscapementComposition.xlsx
