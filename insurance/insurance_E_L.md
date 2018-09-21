## E

**.ear file**

A file used for servlet deployment with IBM WebSphere or BEA WebLogic, each of which uses a slightly different file format. 
This is similar to an Apache Tomcat .war file. 

**earned premium**

The portion of premium that applies to the expired part of the policy period (in other words, the amount of premium that has 
been earned as of a given date). Insurance premiums are payable in advance, but the insurance company does not fully earn 
them until the policy period expires. 

**effective date**

The date that an insurance policy becomes active or in-force. 

**effective time**

The period of time that something is relevant and enforced within a contractual period, independent of the model time. For 
example, if you cancel a year-long auto policy as of August 1, the effective date for the auto policy is January 1 through July 31. 
This independent of the point at which you made this change in model time. See model time. 

**EFT**

Electronic funds transfer. 

**endorsement**

A written form attached to an insurance policy that alters the policy’s coverage, terms, or conditions. These can be extensions 
of coverage, new coverages, or reductions of coverage. For example, an endorsement can be a separate policy for a costly 
wedding ring, that is not fully covered under a homeowner’s policy. You can also use endorsements to customize basic policy 
forms for the requirements of different states. In the insurance industry, many companies use the term endorsement to refer to 
a policy change. Other companies call it a rider. However Guidewire avoids that meaning of the term. (PolicyCenter uses the 
term policy changes instead.) 

**entity**

An entity is a business data model class or instance such as Claim or Policy. Entities are a subset of objects (see object). Entities 
have fields (properties) and in most cases have methods. 

**entity libraries**

See Java API libraries. 

**equity dating**

A process that carriers use to track and monitor surplus or deficit payments collected from insureds. This is in contrast to the 
services provided as of specific dates in the lifecycle of the policy period. 

**event**

An abstract notification of a change in a Guidewire application, such as a new financial transaction on a claim that might be of 
interest to an external system. 

**event date**

The earliest date on which an invoice item or invoice can be billed. BillingCenter places an invoice item on the first available 
planned invoice that occurs on or after its event date. 

**exception**

This defines certain circumstances in which a carrier covers a normally excluded loss. In the BillingCenter Agency Bill process, 
it is the differences between expected gross, net, and commission amounts listed on producer’s monthly statements 
verses actual payments made by a producer. 

**excess**

Similar to a deductible, excess defines a minimum threshold above which the carrier provides compensation for losses. For 
example, carriers provide excess insurance for costs above the threshold for a single large loss or for total costs above the 
threshold for a time period or stop loss. 

**exclusion**

In defining the coverage, carriers often list certain causes of loss that are not covered. For example, a basic homeowners policy 
may exclude earthquake coverage in California unless the policyholder pays extra. 

**exposure**

In ClaimCenter, exposures are defined by the combination of exactly one claimant, one coverage, and one coverage-subtype. 


**exposure earned premium**

The earned premium that is actually exposed to loss during a specified period of time. To develop this earned premium, 
ClaimCenter disregards the date on which premiums were booked. ClaimCenter allocates the portion of the written premium 
exposed to loss (earned) to the exposure period. This is whether the premiums were booked in a prior period, during the current 
period, or after the period. The exposure earned premium eliminates the deficiency contained in accounting earned premium 
that results from timing problems in the recording of the premium. 

**exposure units**

The listed items that are protected under a policy or, more specifically, the units that are used for calculating premiums. The 
most common are vehicles (for auto policies) and locations (for most other policies). For example, a 2008 Jaguar convertible 
will have a higher premium, than a 1990 Honda Civic. 

## F

**final audit**

A process that is applicable to variable basis policies. A final audit contains the verified and ultimate cost for a variable basis 
policy. When the policy is issued, the estimated annual premium (EAP) is based on the policyholder’s best guess at the basis, 
such as payroll, for the entire policy year. The final audit is conducted at expiration or cancellation. A premium auditor 
reviews the policyholder’s records, or the policyholder officially reports the actual payroll amounts for the past policy term. 
The cost of the policy is recalculated using this actual basis amount, and the policyholder is billed or returned the difference. 

**first notice of loss (FNOL)**

The first recording of a claim. In workers’ comp claims, this might be referred to as first report of injury (FROI). This refers to 
both the process of informing the carrier of the loss and to a form often filled out to provide such information. It may be 
entered by an adjuster or a claim intake worker; it may also be transferred electronically from an external system. ClaimCenter 
ensures that this newly opened claim contains a certain minimum amount of information by passing it at the New Loss validation 
level. 

**first-party loss**

Any loss incurred directly by the policyholder, including property damage or loss, injuries, and related costs. In some cases, 
this includes repayment of minor costs associated with fixing the losses of others. For example, minor costs can include those 
associated with an injured guest at a party but for which the injured party does not actually file a claim. The key questions in 
this type of claim are whether the loss is covered and, if so, the amount of the loss for compensation. 

**fixed ID**

In PolicyCenter, this ID describes one refashioned entity in multiple branches, or an entity in a branch with multiple effective/ 
expiration dates. For example, suppose you need to change a car license plate number. The database contains two rows for the 
car. One contains information from before the change. The other contains information from after the change. However, both 
rows have the same revision-independent ID so that the system knows that it is two versions of the same car, not two different 
cars. In previous releases of PolicyCenter, this was called a revision-independent ID (RIID). 

**flat cancellation**

Cancellation of a policy on its effective date as if it had never been issued. No coverage was provided and no premium is due. 

**forms**

These are the documents (template contracts) defining standard types of coverage and endorsements. A policy is made up of a 
series of forms plus a dec sheet (which provides a summary of the benefits provided by the policy). 

**full pay discount**

A feature that allows you to offer a discount for an insured’s policy premium, if full payment is made by a specified date. 

## G

**general ledger**

Collection of all asset, liability, owners' equity, revenue, and expense accounts that itemizes all transactions for each account in 
the chart of accounts. 

**general liability (GL)**

This covers a policyholder for broad categories of liability for third party losses. It is often a component of a commercial or 
homeowners policy 

**Gosu**

An open-source programming language originally written by Guidewire. For more information, see the Gosu Reference 
Guide. 

**Gosu plugin**

See plugin. 

**Gosu templates**

A text-based template file with static information with embedded blocks of Gosu code. The embedded Gosu code includes 
Gosu blocks (<% … %>) and Gosu expression blocks (<%= … %>). Gosu expression blocks (<%= … %>) evaluate Gosu expressions 
and export the result as text. Gosu typically has access to one or more symbols that represent root objects from which to 
extract information, such as a claim field. Also, see template. 

**Guidewire Document Assistant control**

The Guidewire Document Assistant is a Java applet that simplifies document uploading from a Guidewire application to its 
server. 

## H

**hazard**

A hazard is a circumstance that may increase the severity of a loss if one occurs. It is also known as a risk. For example, if you 
have a wood-shingle roof on a home in fire-prone Los Angeles, it is likely to make any fire damage more severe (if a fire 
occurs). Typically, insurers consider these type of issues in the pricing of a coverage, or in considering whether to offer the 
coverage at all. 

Insurers often separate risk into two areas: the physical hazard and the moral hazard. Physical hazard refers to the physical 
aspects of the risk that could make a loss more or less likely, or affect the severity of that loss. Moral hazard refers to the attitude 
and conduct of the insured. While physical hazard can nearly always be addressed by insurers through recommended risk 
improvements, policy conditions and premium rate, moral hazard can only be addressed by declining the risk absolutely. 

**held charge**

A charge for which the insured will not be billed until the hold is released. 

**hold**

In conjunction with trouble tickets, stops a charge from being automatically processed while an account or policy is in dispute. 
A hold blocks automated system behavior while a carrier investigates and corrects a billing problem. 

**homeowners insurance**

A line of business. The typical homeowners insurance policy covers the house, the garage and other structures on the property 
against a wide variety of perils including windstorms, fire and theft. In addition, it usually includes the personal possessions 
inside the house such as furniture, appliances and clothing. The extent of the perils covered depends on the type of policy. An 
all-risk policy offers the broadest coverage. This covers all perils except those specifically excluded in the policy. Homeowners 
insurance also covers additional living expenses. Known as Loss of Use, this provision in the policy reimburses the policyholder 
for the extra cost of living elsewhere while the house is being restored after a disaster. The liability portion of the policy 
covers the homeowner for accidental injuries caused to third parties and/or their property, such as a guest slipping and falling 
down improperly maintained stairs. Coverage for flood and earthquake damage is excluded and must be purchased separately. 

**indemnity**

Payment in compensation for a loss. The goal is to restore a policyholder to the same financial position after the loss as that 
prior to the loss, without the policyholder profiting from the loss. 

**inland marine insurance**

A line of business. This broad type of coverage was developed for shipments that do not involve ocean transport. Covers articles 
in transit by all forms of land and air transportation as well as bridges, tunnels, and other means of transportation and communication. 
Floaters that cover expensive personal items such as fine art and jewelry are included in this category. 

**insurance**

A system to make large financial losses more affordable by pooling the risks of many individuals and business entities. An 
insurance company or some other large group accepts the pooled risks in return for a premium. 

**insured**

Another name for policyholder. 

**interim audits**

An audit process that may be triggered when there is a change to a policy period. 

**invoice**

Often called a bill, an invoice is a commercial document issued by a seller to a buyer. It indicates the products, quantities, and 
agreed prices for products or services that the seller has already provided to the buyer. In BillingCenter, an invoice is an itemized 
bill requesting payment on a charge for a policy. An invoice indicates that, unless paid in advance, payment is due by the 
insured to the carrier according to the agreed terms. 

**invoice date**

The date an invoice is billed. Invoice date is also called billing date or statement date. 

**invoice item**

A line item that represents all or part of a charge. For example, a premium charge on a billing instruction can be divided into a 
down payment and monthly installments. The down payment and each installment becomes an item on an invoice. The total 
amount of the invoice items equals the total charge amount. BillingCenter adds invoice items to invoices or producer statements. 


**invoice stream**

A set of invoices. In BillingCenter, all invoices are contained in an invoice stream. All invoice streams in the BillingCenter 
base configuration are spaced at a regular intervals such as monthly and twice monthly. 

**ISO**

ISO (originally known as the Insurance Services Office) is the leading United States provider on information and standards for 
many types of insurance. ISO provides a service called ClaimSearch which helps detect duplicate and fraudulent insurance 
claims. If an insurance company enters a claim, the company can send details to the ISO ClaimSearch service, and get reports 
of potentially similar claims from other companies. ClaimCenter includes built-in integration to ISO ClaimSearch. 

**issuance**

The process of issuing all the formal paperwork for the policy, updating various policy and billing systems about the new policy, 
and delivering it to the insured. 

## J

**Jakarta**

See Tomcat. 

**Java API libraries**

Java libraries that let you write Java code that accesses entity data and runs inside the Guidewire application JVM. 

**Java plugin**

See plugin. 

**JMX**

Java Management Extensions (JMX) provides the tools for building tools for managing and monitoring devices, applications, 
and service-driven networks. Guidewire applications provide JMX support through support of an abstracted management 
plugin. Guidewire provides an example management plugin that implements JMX. 

**jobs**

In PolicyCenter, jobs coordinate all of the work associated with creating or changing a PolicyPeriod. While it is called a job 
in the data model, the PolicyCenter interface lists completed jobs as Policy Transactions. Subtypes of PolicyCenter jobs include: 
submission, issuance, renewal, rewrite, policy change, cancellation, reinstatement, and audit. 

**Journal**

That part of the BillingCenter underlying double entry accounting system that tracks all transactions by T-account owner. 

## K

**kidnap / ransom insurance**

Coverage up to specific limits for the cost of ransom or extortion payments and related expenses. Often bought by international 
corporations to cover employees. Most policies have large deductibles and may exclude certain geographic areas. Some 
policies require that the policyholder not reveal the existence of the coverage. 

## L
**late binding**

A special messaging feature that Guidewire applications use to include entity fields in a message payload. The Guidewire 
application only evaluate these fields immediately before sending the message to a destination. This is in contrast to evaluating 
the entity fields at message generation time, also known as early binding. Typically use early binding. 

However, use late binding for an entity public ID field if another message acknowledgement or API can change the public ID 
before the current message is sent. 

**lead time**

The number of days that must be allowed between the invoice billing date and the due date. In BillingCenter, you can specify 
two different lead times. Lead Time is used in cases where the carrier bills the customer directly. Non Responsive Lead Time 
applies in cases where the payment is automatic with no response required of the customer. 

**leakage**

Claims payments beyond those necessary to satisfy a typical claimant. 

**Ledger**

That part of the BillingCenter underlying double entry accounting system that tracks all T-accounts and line items associated 
with a T-account owner. 

**liability insurance**

Insurance for what the policyholder is legally obligated to pay because of bodily injury or property damage caused to another 
person. 

**library**

A library is a collection of functions that you can call from within your Gosu programs. Guidewire provides a number of standard 
library functions (in gw.api.* packages, for example). 

**limit**

Most coverages set a limit on the maximum amount that will be paid. These limits may be set on a per incident basis (a maximum 
payment per auto accident) or on an annual basis (a maximum total amount paid in any policy year). 

**line item**

Identifies the actual item expense. 

**line of business**

Line of business has different definitions in different contexts. In BillingCenter and PolicyCenter, it usually means the type of 
insurance policy, such as an umbrella or workers’ compensation policy. 

**loss**

Loss broadly refers to any type of loss, including any of the following: 

• repair or replacement costs for damaged or stolen property 

• costs associated with treatment of an injury, lost wages, and less tangible losses for pain and suffering, scarring, and so on 

• lost business revenues or extra costs associated with loss of use of a home, vehicle, or business property 

**Loss Adjusting Expenses (LAE)**

Costs for the insurance company to investigate and resolve the claim. These include internal costs of salaries, equipment, supplies, 
and so on, and payments to third parties for inspection, litigation defense, and so on. 

**loss costs**

Indemnity payments made by the insurance company to the policyholder or to a third party on behalf of the policyholder. 

**loss reserves**

An insurer's estimate of the amount an individual claim will ultimately cost. On an insurer's financial statement, it is the 
amount of estimated liabilities for known claims not yet paid and incurred but not reported claims. 
