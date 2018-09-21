## C

**cancellation job** 

The termination of an in-force insurance contract by either the insured or the insurer. Termination may be voluntary, involuntary, 
or mutual in accordance with provisions contained in the contract. 

**carrier** 

The insurance company that provides the policy to the insured. 

**carry forward (exception)** 

A way to resolve an agency bill exception by stating that the amount in question will be paid in the next billing cycle. 

**casualty** 

Refers to losses to property, bodily injuries, or other losses caused by an accident. 

**catastrophe** 

Term used for statistical recording purposes. It refers to a single incident or a series of closely related incidents causing severe 
insured property losses totaling more than a given amount, for example, $25 million. It describes an event (such as earthquake, 
storm, or flood) that causes many losses that can all be linked to the same broader cause. Carriers need to track claims related 
to catastrophes for reporting (internal and regulatory) and to collect on catastrophe reinsurance. Carriers also frequently assign 
special teams to handle the huge number of simultaneous claims in an expedited manner. 

**cause of loss**

Categorizes the reason for loss. Some common examples are collision for vehicles, theft, or natural causes like hail, wind, 
earthquake, and flooding. Some companies also call these categories perils. 

**charge**

The fundamental invoicing unit that the policy administration system sends to BillingCenter in a billing instruction. A billing 
instruction must contain at least one charge. BillingCenter then translates each charge into invoice items on an invoice or statement. 
Each charge includes the amount to be invoiced and a description. 

**charge date**

The date BillingCenter receives the billing instruction that contains the charge. The charge date can influence how 
BillingCenter places invoice items on invoices. 

**charge effective date**

The date the coverage or coverage reduction specified by the charge takes effect. The charge effective date depends on the type 
of billing instruction. For a new policy, the charge effective date is the same as the policy period's effective date. For an existing 
policy, it is the same as the effective date of a billing instruction for an existing policy (such as a policy change or a cancellation). 
The charge date can influence how BillingCenter places invoice items on invoices. 

**charge hold**

A mechanism that prevents BillingCenter from continuing to bill the insured for any disputed amounts. A charge hold also prevents 
BillingCenter from charging late fees and from applying a delinquency to the account while there is an active dispute 
investigation in process. 


**charge invoicing**

The process in BillingCenter of dividing charges into invoice items and assigning the items to invoices in an invoice stream. 

**charge pattern**

A template for a charge that determines how BillingCenter handles the charge in terms of invoicing. For example, the Premium 
charge pattern specifies an invoicing approach of Down Payment and Installments whereas the Taxes charge pattern 
specifies an invoicing approach of One-time charge. BillingCenter associates each charge with a single charge pattern. 

**charge pattern categories**

Categories include: General, Premium, Fee, Tax, and Recapture. 

**charge reversal**

A type of transaction in BillingCenter that reverses charges made in error instead of reversing an amount that cannot be collected. 
In this way, they relate somewhat to write-offs. 

**claim**

A general term referring to all the different losses that arise from a single incident and a single policy. It is possible that a single 
incident (a flood, for example) can affect many policyholders leading to many claims. However, all damages to a particular 
policyholder for the actual flooding event (injuries, damages to a building, lost or damaged furnishings, for example) fall 
under the same claim. 

ClaimCenter and PolicyCenter use a different data model structure for a claim. 

**claim suffix**

The claim may include a suffix to reference a discrete piece of a claim or a specific exposure with a single type of loss. This 
term is sometimes used because these separate claimant/loss issues are frequently identified in old legacy claims systems with 
a letter suffix such as 0034563B. This can indicate claim number 0034563 with suffix B for the second issue or “line” of the 
claim. 

**claimant**

This refers to a person involved in a claim who requests compensation for a loss. This often refers to third parties who make 
liability claims against the policyholder. However, it can also indicate the policyholder in first party loss claims. As it is possible 
to incur multiple types of losses from a single incident, it is possible to have multiple claimants for a single claim. However, 
an exposure can have only one set of claimants, either first party or third party, but not both. 

**class code**

A code that identifies the type of risk. In workers’ comp, it is a four digit code that identifies the activities of the business, or 
more precisely its employees. In commercial auto, the class code describes the type of vehicle, its use and range of use. In general 
liability, the class code describes the type of business activities being insured. In the context of statistical reporting, it is a 
subset of the possible stat codes. 

**collateral**

An additional asset or amount that the carrier requires of an insured to secure coverage for a new or renewed policy. The 
insured can satisfy the collateral requirement with cash, letters of credit (LOC), or a combination of both. The collateral 
deposit is subject to seizure in the event of delinquency. 

**collection agency**

A third-party organization that a carrier uses to collect unpaid funds. If an account becomes delinquent, an event in the delinquency 
process can trigger the assignment of a collection agency as the payer of past due invoices. In BillingCenter, a collection 
agency is an account type. 

**collision**

Coverage for losses to the insured’s vehicle due to an accident, such as hitting another vehicle, a tree, or an animal. 

**commercial package policy (CPP)**

A single product that typically consists of two or more policy lines packaged together as a single policy. Included lines of business 
can be: commercial, general liability, commercial property, commercial auto, crime, boiler and machinery, and inland 
marine. 

**commission**

A portion of the policy premium (a percent) that is paid to a producer or insurance salesperson. The percentage varies widely 
depending on coverage, the insurer, and the marketing. 

**commission plan**

A set of rules and attributes that determine the amount of commission paid to a producer (or producers) after the producer sells 
a new policy or renews an existing policy. 

**command**

The basic building block of the interface-level integration framework for a Guidewire application. A command expresses an 
action to perform anytime that you do something in the ClaimCenter interface. For example, a command can open a browser 
window and take you to another (related) web application. 

**command shell**

The context in which the services operate, giving the services the ability to discover and call each other. As part of initialization, 
the command shell starts each service, giving the service a reference to the shell and letting services get references to 
each other. 

**commercial lines**

Products designed for and bought by businesses. Among the major coverages are boiler and machinery, business income, commercial 
auto, comprehensive general liability, directors and officers liability, fire and allied lines. These can also include inland 
marine, medical malpractice liability, product liability, professional liability, surety and fidelity, and workers’ compensation. 

You can purchase most of these commercial coverages separately except business income, which you can only add to a fire 
insurance (property) policy. 

**comprehensive**

Coverage for all other vehicle damage and contents, such as fire, theft, hail, vandalism, and so on. 

**contacts**

Details of the contact information for an account. Each account must have a primary contact. The primary contact is either a 
business entity (company) or an individual associated with the account. ClaimCenter stores contact information within the 
application itself. 


**contractual period**

A single policy term from the date the policy goes into effect (the effective date) to the date it expires (the expiration date). 
Generally speaking, a policy cannot have contractual periods that overlap in effective time. However, in some cases, it is possible 
for the contractual periods in a policy to overlap due to a policy cancellation or modification. 

**coverable**

A coverable is an exposure to risk. (The intent of a policy is to mitigate that risk.) A coverable is a tangible property item, a 
location, a jurisdiction, or the policy itself. Within PolicyCenter, Guidewire makes the policy line a coverable to represent the 
named insureds. PolicyCenter attaches coverages only to coverables. 

**coverage**

A coverage is protection from a specific risk. PolicyCenter always attaches coverages to a coverable. There are two types of 
coverages: property and liability. To illustrate, on an automobile policy, a collision property coverage protects the insured's 
vehicle and a liability coverage protects the driver for damage done to another vehicle. 

**coverage period**

A carrier generally provides insurance against losses that occur during a specified period, regardless of the time that you discover 
or report the loss. For liability coverages, this usually takes the form of providing coverage based on the date of the 
actual harm. It can also take the form of coverage based on the date in which the claim is made against the insured. Coverage 
based on the date of the actual harm is the most common. Many insurance companies call a coverage based on the date in 
which the claim is made a Claims Made coverage. (Professional Malpractice Liability or Directors and Officers Liability 
occasionally makes use of this type of coverage.) 

**cycle**

A container for either an agency bill statement or promise that is usually generated monthly for agency bill producers. 

## D 

**data extraction**

Services and tools to export a Guidewire application’s data into external formats in external systems, initiated by external code 
or systems. For example, an external system can request HTML versions of claims, structured XML versions of claims, or 
other custom formats using Gosu templates. 

**data model**

The description of the database representation of all entities which are part of a Guidewire application (such as Claim, Policy, 
and Contact) and typelists (like the possible values of LossType). 

**data model extensions**

Additions to the business entities that Guidewire provides in the base configuration data model. You use extensions to add new 
fields (properties) to an existing base entity or to create a new entity with custom fields. ClaimCenter treats extension entities 
in an identical manner to base entities. 

**database authentication plugin**

Plugin that authenticates the connection between a Guidewire application and its database. You can also use a database authentication 
plugin to authenticate to an external address book application with the IAddressBookAdapter plugin. 

**dec page or declarations page**

A policy is made up of a boilerplate legal document, various additional pages for endorsements, and a declarations page which 
customizes the contract for the specific client. The Dec page contains the selected coverages, limits and deductible options set, 
endorsements listed, and premiums indicated. This is probably the only page of the insurance policy that most people ever 
read. 

**deductible**

The amount of loss paid by the policyholder. Either a specified dollar amount, a percentage of the claim amount, or a specified 
amount of time that must elapse before benefits are paid. The bigger the deductible, the lower the premium charged for the 
same coverage. 

**deferred premium payment plan**

Initially, companies developed this concept for multi-year (three- or five-year) policies, in which you could pay the premium 
in annual installments. As policy premiums increased, companies expanded this concept to include annual policies, in which 
the premium payment is made over the course of the year in quarterly or monthly payments. 

**delegate**

A delegate is a declaration of a Gosu class that contains methods and properties that can take responsibilities for actions and 
data storage for another object. These can be used to link to objects with shared code implemented by the delegate rather than 
duplicated in each class that might use a delegate. For example, a delegate encapsulates behaviors that attach a coverage to a 
coverable or a modifier to a modifiable. 

**delinquency**

An automatic or manual spawned process that launches and/or coordinates the steps necessary to cancel or reinstate a delinquent 
entity, and/or to write off the delinquent amount. 

**delinquency plan**

A set of rules or attributes that specify how to handle an account or policy period delinquency. The delinquency plan defines a 
set of reasons for a delinquency. Each reason has an associated workflow that BillingCenter invokes when an account or policy 
period becomes delinquent, and the delinquency reason matches the reason in the delinquency plan. 

**delinquent**

The state of a policy, account, or producer that has past-due charges. This generally assumes the expiration of any grace period 
for paying the past due charges. 

**destination**

Abstraction of an external system to which Guidewire application messages can be sent, for example a mainframe, a proprietary 
email system, or a check printing service. Each destination may be interested in different events. Each destination includes 
a message request plugin. Each destination can also include an optional message request plugin (typically for pre-processing) 
and an optional message transport plugin (for handling asynchronous replies). 

**direct bill 

The billing process used by BillingCenter to directly bill (invoice) customers for charges invoiced to their accounts. The direct 
bill process also handles commission payments to producers on an agreed-upon schedule. 

**direct writers**

Insurance companies that sell directly to the public using exclusive agents or their own employees, through the mail, the inter-
net, or by telephone. Large insurers, whether predominately direct writers or agency companies, are increasingly using many 
different channels to sell insurance. In reinsurance, denotes reinsurers that deal directly with the insurance companies they 
reinsure without using a broker. 

**directors and officers liability insurance (D&O)**

Directors and officers liability insurance covers directors and officers of a company for negligent acts or omissions and for 
misleading statements that result in suits against the company. There are a variety of D&O coverages. Corporate reimbursement 
coverage indemnifies directors and officers of the organization. Side-A coverage provides D&O coverage for personal 
liability if the firm does not indemnify the directors and officers. Entity coverage, for claims made specifically against the 
company, is also available. You can also broaden a D&O policy to include coverage for employment practices liability. 

**disbursements**

A refund that returns funds from an account to a customer or producer. The disbursement has a trigger date (the creation date 
of the distribution). BillingCenter also assigns a dollar amount and a due date (day of distribution.). Information specified in 
the billing plan associated with the customer account triggers the distribution. 

**disposition**

Specifies how BillingCenter will handle an exception on an item when an agency bill payment or promise is executed. Options 
include Carry Forward, Exception, Writeoff, and Automatic. 

**distribution method**

Account-level logic that indicates how money is distributed if the amount received does not match the amount invoiced. 

**DMZ**

De-Militarized Zone. A networking term for a network configured with network firewalls so that it is accessible from the outside 
world but partitioned off from the main internal network. For example, in ClaimCenter, DMZs allow ISO to respond to 
ClaimCenter through a callback URL. Thus, you do not need to expose ClaimCenter servers to the external Internet. See bastion 
host. 

**document merge plugin**

Plugin that integrates with the ClaimCenter interface to extract data from the application, which it then uses to populate a letter 
from a document template. A document merge plugin can also populate other document types, such as a spreadsheet for calculating 
benefits or estimating reserves. ClaimCenter typically includes default behavior for these actions. You can also implement 
your own plugins to handle other document types. 

**document source plugin**

Plugin that integrates with the ClaimCenter interface to access a remote repository of documents. Guidewire applications 
implement this plugin with a default documentation source. However, if you want, you can implement a custom document 
source that interacts with a remote Document Management System. 

**document template**

Document source file, such as a Microsoft Word file, that the document template’s template descriptor file populates with 
application data. 

**document template descriptor**

Plugin interface that describes an actual document template such as a Microsoft Word mail merge template, an Adobe PDF 
form, or a Gosu template, for example. The IDocumentTemplateDescriptor interface defines the API interface for an object 
that represents a document template descriptor. Guidewire provides a default implementation of this interface that reads the 
template information from a standard XML file. (You can customize this XML file to meet your business needs.) 

**domain method**

A method (function) associated with a Guidewire entity. If Gosu code has a reference to an entity, you can get or set fields on 
the entity, and also call domain methods on the entity. 

**double entry accounting**

An accounting system in which every transaction has at least two balancing journal entries of debits and credits, with debits 
always equal to credits. Double-entry accounting keeps the accounting equation in effect and is the basis for all manual or 
automated accounting systems. Every transaction affects at least two accounts, since there must be at least one debit and one 
credit for each transaction. Entries that are not made to a balance sheet account are made to an income or expense account. 

**due date**

The last date an invoice can be paid before it becomes past due. 

**due date invoicing**

A method used by BillingCenter to determine invoice dates during charge invoicing. In due date invoicing, the relevant 
invoice day specified on the account is used to establish the due dates for account invoices. For example, the Every Other 
Week - Anchor Date setting is used for every other week invoicing. Invoice dates are then calculated by subtracting the lead 
time (specified in the associated billing plan) from the due date. Contrast with bill date invoicing. 
