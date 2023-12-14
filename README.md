Background: This dataset contains vehicle dataset - attribute, model, accident details, etc along with policy details - policy type, tenure etc

Modelling objective: To predict if the vehicle insurance claimed is fraudulent or not. Binary: 1 or 0

Target variable: FraudFound_P

The dataset contains 15420 observations and 33 variables.

Variable        Description

Month           month name, object

WeekOfMonth      numeric

DayOfWeek        numeric

Make            contains a list of 19 car manufacturers

AccidentArea     classifies area for accident as "Urban" or "Rural"

DayOfWeekClaimed   contains the day of the week the claim was filed

MonthClaimed       the month where the vehicle insurance was claimed

WeekOfMonthClaimed     numeric, the week of the month where the vehicle insurance was claimed

Sex                  gender of individual making claim

MaritalStatus       marital status of individual making claim

Age              ages of individual making claim

Fault           categorization of who was deemed at fault

PolicyType    contains two pieces of info -
              the type of insurance on the car - liability, all perils, collision
              category of the vehicle - sport, sedan, utility.

VehicleCategory   contains the categorization of the vehicle (see PolicyType)

VehiclePrice       contains ranges for the value of the vehicle 

FraudFound_P     indicats whether the claim was fraudulant (1) or not (0)

PolicyNumber     the masked policy number, appears to be the same as row number minus 1

RepNumber       rep number is integer from 1 - 16

Deductible       the deductible amount

DriverRating     the scale is 1, 2, 3, 4

Days_Policy_Accident  this is the number of days between when the policy was purchased and the accident occured

Days_Policy_Claim     this is the number of days that pass between the policy was purchased and the claim was filed

PastNumberOfClaims   previous number of claims filed by policy holder

AgeOfVehicle      represents age of vehicle at time of the accident

AgeOfPolicyHolder    each value is a range of ages"

PoliceReportFiled    indicates whether a police report was filed for the accident

WitnessPresent    indicted whether a witness was present

AgentType      this classifies an agent who is handling the claim as internal vs external

NumberOfSuppliments  not sure what a suppliment is in insurance

AddressChange_Claim    time from claim was filled to when person moved (i.e. filed an address change)

NumberOfCars    number of cars involved in accident OR number of cars covered under policy

Year    guess, year accident occured

BasePolicy    type of insurance coverage (see PolicyType)


