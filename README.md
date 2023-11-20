# BT4012_G7

Columns in X_train, X_test
numerical_cols = [
    "AdmitForDays",
    "Age",
    "ClaimProcessedForDays",
    "DeductibleAmtPaid",
    "IPAnnualDeductibleAmt",
    "IPAnnualReimbursementAmt",
    "InscClaimAmtReimbursed",
    "NoOfMonths_PartACov",
    "NoOfMonths_PartBCov",
    "OPAnnualDeductibleAmt",
    "OPAnnualReimbursementAmt",
]
categorical_cols = [
    "AttendingPhysician_ce",
    "ClaimID",
    "ClmAdmitDiagnosisCode_ce",
    "ClmDiagnosisCode_10_ce",
    "ClmDiagnosisCode_1_ce",
    "ClmDiagnosisCode_2_ce",
    "ClmDiagnosisCode_3_ce",
    "ClmDiagnosisCode_4_ce",
    "ClmDiagnosisCode_5_ce",
    "ClmDiagnosisCode_6_ce",
    "ClmDiagnosisCode_7_ce",
    "ClmDiagnosisCode_8_ce",
    "ClmDiagnosisCode_9_ce",
    "ClmProcedureCode_1_ce",
    "ClmProcedureCode_2_ce",
    "ClmProcedureCode_3_ce",
    "ClmProcedureCode_4_ce",
    "ClmProcedureCode_5_ce",
    "County",
    "DiagnosisGroupCode_ce",
    "Gender",
    "OperatingPhysician_ce",
    "OtherPhysician_ce",
    "Provider",
    "Race",
    "State",
]
bool_cols = [
    "ChronicCond_Alzheimer",
    "ChronicCond_Cancer",
    "ChronicCond_Depression",
    "ChronicCond_Diabetes",
    "ChronicCond_Heartfailure",
    "ChronicCond_IschemicHeart",
    "ChronicCond_KidneyDisease",
    "ChronicCond_ObstrPulmonary",
    "ChronicCond_Osteoporasis",
    "ChronicCond_rheumatoidarthritis",
    "ChronicCond_stroke",
    "RenalDiseaseIndicator",
    "isDead",
    "is_inpatient",
    "RenalDiseaseIndicator",
]

Columns in y_train
categorical_cols = [
    "BeneID",
    "Provider",
]
bool_cols = [
    "PotentialFraud",
]