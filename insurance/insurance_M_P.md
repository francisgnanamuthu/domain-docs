## M

**marine insurance**

Coverage for goods in transit, and for the commercial vehicles that transport them, on water and over land. The term can apply 
to inland marine but more generally applies to ocean marine insurance. Covers damage or destruction of a ship’s hull and 
cargo and perils include collision, sinking, capsizing, being stranded, fire, piracy, and jettisoning cargo to save other property. 
Wear and tear, dampness, mold, and war are not included. 

**medical payments**

Another type of first-party medical coverage, thus similar to a PIP (personal injury policy). Also known as MedPay. 

**MedPay**

See medical payments. 

**message / message payload**

An abstract encapsulation of information sent form a Guidewire application to an external system in response to an event. A 
Guidewire application can send one or more messages to each message destination interested in each event. Each message has 
a message ID, status information, and a message payload. The payload is the main data content in text format of the message. 

**message reply plugin**

A plugin that implements asynchronous replies to messages from remote systems, and optionally performs post-processing 
such as field updates to application data. These plugins implement the plugin interface MessageReply. You only need to implement 
this type of plugin if you need to send messages asynchronously. If the MessageTransport plugin can send the message 
synchronously, then there is no need to define a message reply plugin. 

**message request plugin**

Plugin that implements optional pre-processing of a message, and optional post-send (not post-acknowledgement) message 
processing. This type of plugin implements the MessageRequest plugin interface. 

**message transport plugin**

Plugin that implements sending of a message on some transport such as a messaging queue, a remote procedure call, or any 
other custom transport to an external system. If the transport is capable of synchronous acknowledgements, this plugin can 
acknowledge the message and optionally perform post-processing such as field updates. This type of plugin implements the 
MessageTransport plugin interface. 

**message without primary**

Another name for non-safe-ordered message. The messaging destination user interface uses the term message without primary. 

**messaging plugin**

Plugin that implements one of three types of messaging plugin interfaces for the purpose of preparing or sending a message. 
The three types of messaging plugins are: message reply plugin, message request plugin, and message transport plugin. See 
those glossary entries for details. 

**mid-term change**

In PolicyCenter, a request for a change to an in-force policy. 

**model number**

In PolicyCenter, a model number identifies different branches associated with a policy. When PolicyCenter promotes a branch, 
PolicyCenter assigns a new model number, one greater than the previously most recently promoted branch on its period. This 
is a read-only property. Contrast with term number, which starts with 1 and increments by 1 only for renewals or rewrites. 

**model time**

In PolicyCenter, the real-world date and time that a version of the policy (or other object) was bound. See effective time. 

**modifier**

A value used by the rating engine to adjust the policy quote (or some portion of the quote). Modifiers capture information relevant 
to the pricing of a policy that is not necessarily tied to a specific coverable or coverage. 

**MVR**

A motor vehicle record (MVR) is documentation pertaining to a driver’s driving history. It contains information such as identifying 
data, license status, convictions, traffic violations, accidents, license suspensions, and revocations on file with the 
driver’s home state. The information in this report usually comes from state DMVs (Department of Motor Vehicle) and can 
vary by state. Carriers typically use MVRs to evaluate the risks associated with a given driver. Violations are assigned point 
values, with more severe violations having a higher point value. High MVR point totals indicate high risk drivers, and often 
result in higher policy premiums. 

## N 

**NAIC**

The National Association of Insurance Commissioners is the organization of insurance regulators from the 50 states, the District 
of Columbia and the five U.S. territories. The NAIC provides a forum for the development of uniform policy when uniformity 
is appropriate. 

**name clearance**

The process of checking against one or more producer/account databases to ensure that a person or company is not an existing 
account in PolicyCenter. This is to ensure that another producer does not represent the person or company for the given policy 
type. PolicyCenter searches existing accounts for name clearance before it creates a new account. 

**named insured**

An individual, business or organization that is specified in the declarations by name as the insureds under a policy. Other 
insureds may be covered without being named, but can be included for coverage as insureds or additional insureds by other 
provisions (as in the policy definitions). The named insured is responsible for premium payments, receipt of notices, and 
adjustment of losses. 

**named peril**

Peril specifically mentioned as covered in an insurance policy. 

**NCAD**

Notice of Cancellation at Anniversary Date 

**NCCI**

The National Council on Compensation Insurance is a U.S. insurance rating and data collection bureau specializing in workers' 
compensation. 

**non-disclosure**

The withholding of information from an insurer. If there has been non-disclosure prior to inception, then the insurer is able to 
cancel the contract and can possibly reduce its liability to the insured. If the non-disclosure was fraudulent, then the insurer has 
the right to avoid the contract from its inception. If the insured’s non-disclosure was innocent, then the insurer can still attempt 
to reduce it liability under the policy. However, the insurer must prove that, if it had known the true situation at the time, it 
would have structured the policy terms and/or premium differently. If proven, this reduces the insurer’s liability to an amount 
that puts the insurer in the same position it would have been in had the non-disclosure not occurred. 

This is different from misrepresentation. Misrepresentation is the provision of information which is subsequently found to be 
incorrect. 

**non-safe-ordered messages**

See safe-ordered messaging. 

**notice of loss**

Notice the insured provides to the insurer that a loss has occurred. 

**NPW**

Net Premiums Written. 

## O

**object**

An object is an instance of any class such as ArrayList, Claim, or Activity (See entity). 

**out-of-sequence job or transaction**

Policy changes or other jobs that are not bound in sequential order as compared to the effective dates of the already bound revisions. 
If a new revision’s policy period effective date is earlier than a policy period effective date of another revision within 
that period, then Guidewire considers this to be out-of-sequence. The effective date is the start of the effective date range. 
Guidewire calls any work order that creates this sequencing issue an out-of-sequence work order, and it applies to policy 
change, cancellation, and reinstatement jobs. 

Sometimes other companies call these items out-of-sequence endorsements, but Guidewire avoids this term because of the 
other meaning of endorsement (see endorsement). 

## P

**paid through date**

The day through which premium has been earned. The paid through date is used in calculating policy equity. 

**payload**

See message / message payload. 

**payment**

These represent actual payments to claimants (or to service providers on behalf of claimants) or to vendors for loss adjusting 
expenses. In BillingCenter, this is a sum of money (a receipt) sent to a carrier to apply to a BillingCenter account. Payments 
consist of an insured receiving and paying an invoice, an automatic deduction for an installment payment, or a deposit on a 
new policy period which has not been invoiced. 

**payment item**

When a payment is made, the portion of a payment that is applied to a specific item is the payment item. 

**payment plan**

A set of rules or attributes that detail how BillingCenter converts charges on a billing instruction into individual invoice items. 
For example, a payment plan might specify that a premium charge is to be divided into a 10% down payment item and a maximum 
of 10 installment items. Contrast with billing plan. 

**peril**

A specific risk or cause of loss covered by an insurance policy, such as a fire, windstorm, flood, or theft. A named-peril policy 
covers the policyholder only for the risks named in the policy in contrast to an all-risk policy, which covers all causes of loss 
except those specifically excluded. 

**period**

In PolicyCenter, it is a single policy term from the date the policy goes into effect (the effective date) to the date it expires (the 
expiration date). 

**personal injury**

Distinguished from bodily injury, this term relates to injury inflicted by way of false arrest, invasion of privacy, malicious 
prosecution, and so on. It is written as Coverage B of the commercial general liability forms and as homeowners Coverage E. 

**Personal Injury Protection (PIP)**

Portion of an auto insurance policy that covers the treatment of injuries to the driver and passengers of the policyholder’s car. 
In most cases, people have separate medical insurance that provides primary coverage for injuries. Also known as PIP. 

**personal lines**

Property or casualty insurance products that are designed for and bought by individuals, including homeowners and automobile 
policies. 

**personal property / contents**

First party coverage for losses to moveable items such as furniture, office equipment, or art, that is covered by a policy. 
Although high value items can be itemized, most coverage is for all personal property contained in the covered building (the 
contents of the home). 

**physical damage (PD)**

Commonly refers to vehicle damage losses (as opposed to contents, injuries, and so on) in an automobile claim. 

**plan**

The container of the different types of customizable plans in BillingCenter. BillingCenter uses plans to automate and control 
many of its processes. This includes administering bills, paying commissions to producers, starting delinquency processes, and 
customizing how payments are applied to accounts and policies. 

See also agency bill plan, billing plan, commission plan, delinquency plan, and payment plan. 

**plugin**

Plugins are mini-programs that a Guidewire application invokes to perform an action or calculate a result. The Guidewire 
application includes a plugin interface that defines the set of required methods for any implementation. An example of a plugin 
that calculates a result is a claim generation plugin, which returns a new claim number. An example of a plugin that performs 
an action is a messaging plugin, the purpose of which is to send a message to an external system. It is possible to implement a 
plugin in either Gosu or in Java. If you write your plugin implementation in Java, Guidewire recommends using OSGi to 
encapsulate your plugin code. In Studio, use the Plugins Registry to specify that a Gosu class, Java class, or OSGi bundle 
implement that plugin interface. 

**policy**

A written contract for insurance between an insurance company and policyholder stating details of coverage. The policy 
defines what items or risks are being covered, what set of coverages has been purchased, and the time period of coverage. For 
example, a personal auto policy lists a set of vehicles and covered drivers. It also lists a set of coverages for: collision, comprehensive, 
towing, rental car, uninsured/under-insured motorist, medical payments, and liability. 

A policy protects the insured from accidental loss (not intentional actions, except for Surety, which is not strictly insurance at 
all). For liability coverages, this means that the policy insures against negligence (legal term) but not malice. Each policy type 
provides a set of coverages, which protect against specific types of losses and set limits and deductibles. The policy also lists 
the people or property to be insured against loss. The structure of the policy data model varies among Guidewire applications. 

**Policy (entity)**

In PolicyCenter, this refers to all versions of a single policy over multiple policy periods. For example, each time that you 
change an automobile policy, perhaps by adding a new driver or vehicle, PolicyCenter creates a new version of the policy. 
However, there is still only a single Policy entity for the policy. 

**Policy Administration System (PAS)**

Computer systems that contain the policies and all their histories. They can vary in their breadth of functionality, but generally 
share certain characteristics. These include tracking policy data, managing different policy versions, handling LOB variations, 
ties to billing systems, and meeting statutory reporting, notifications and regulatory requirements. 

**policy equity**

The difference between the paid amount and the earned premium as of a given date. 

**policyholder**

The person or business entity that forms a contract with the carrier to insure risks. Typically, the policyholder is protecting 
themselves from losses to owned property, people, or liability for other people's losses. 

**PolicyPeriod (entity)**

A policy can have multiple policy periods. A policy period represents a single contract period within a policy. For example, 
every time that you renew a policy, PolicyCenter creates a new contract covering the new time period. This action creates a 
new policy period. The policy period and its children (for example, Audit Schedule Items) represent data that describes the 
entire policy period, not just a single version of the policy. 

**preemption**

The situation that arises when two concurrent PolicyCenter changes are based on the same branch. When the second one finishes, 
you must merge changes from recently-bound jobs into the active job before binding the active job. 

**premium**

The price of an insurance policy, typically charged annually or semiannually. There are direct, earned, and unearned premiums. 


**premium reporting**

Allows you to manage this billing process where insureds provide periodic reports to their Policy Administration System 
(PAS) that detail their actual exposure which tends to changes over time. 

**primary entity and primary object**

A primary entity represents a type of high-level object that a Guidewire application uses to group and sort related messages. A 
primary object is a specific instance of a primary entity. Each Guidewire application specifies a default primary entity type for 
the application, or no default primary entity type. Additionally, messaging destinations can override the primary entity type, 
and that setting applies just to that messaging destination. Only specific entity types are supported for each Guidewire application. 
See safe-ordered messaging for more details. 

Contrast with the term root object. 

**primary named insured**

The name which appears as the policyholder on the declarations page. The primary named insured is the first named insured in 
the policy contract and receives the policy contract, notifications, and other documentation. Other named insureds may be 
defined for a policy. The primary named insured represents all named insureds with regard to contract requirements, contract 
changes or termination. However, other named insureds are equally insured under the policy provisions. See named insured. 

**producer**

This is a generic term for any third party who brings business to the carrier. Except in the case of captive agents, the client relationship 
is owned by the producer. Carriers pay commissions to the producer for bringing in new business and getting the clients 
to renew their policies. Carriers compete for the business through the producers, so both price and service to end clients 
and service and compensation to the producers matters. In BillingCenter, producers can participate in either agency bill or 
direct bill processes (or both). 

**producer code**

The policy administration system (PAS) can generate a set of codes, and assign one or more of these codes to each agent or 
broker with which the carrier does business. This code is the key to transacting business with producers. For example, the 
terms of the contract with the producer, and the payments made to the producer are all structured with producer codes. In 
BillingCenter, the producer code associates a producer with a commission plan. 

**producer payment**

Payments to producers that include outgoing payments for commissions that can be processed either manually or automatically. 


**producer statement**

A bill that is sent to an agency bill producer. It provides a list of all of the producer’s invoices for a given month and indicates 
which payments the carrier expects from the producer for that month. 

**promise to pay**

A document submitted by an agency bill producer (agent) using the BillingCenter Account Current process. The promise to 
pay describes the payments the producer expects to make to the carrier for the period. 

**promoted (or bound)**

A branch that was made legally binding. 

**property**

Property refers to any owned real property or buildings, personal property, and vehicles. This term also refers to first party 
coverage for damage to buildings, such as homes or office buildings. 

**property / casualty insurance (P&C)**

Covers damage to or loss of policyholders’ property and legal liability for damages caused to other people or their property. 
Property/casualty insurance, which includes auto, homeowners, and commercial insurance, is one segment of the insurance 
industry. The other sector is life/health. Outside the United States, property/casualty insurance is referred to as nonlife or general 
insurance. Guidewire creates insurance software for the P&C sector. 

**public ID**

A string of characters that uniquely identifies an entity (a business record) in a Guidewire application. A public ID sometimes 
corresponds to a record ID in an external system. However, in some cases (such as the web service APIs) the application can 
create it for you. All entities have a public ID if they are identified in the application’s Data Dictionary with the keyable attribute. 
Public IDs must be unique for that type of entity, but different entities can share the same public ID without problem. 
