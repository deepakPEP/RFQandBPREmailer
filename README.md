# Pepagora Email Templates

This folder contains all the HTML email templates used by the Pepagora B2B marketplace platform. These emails are sent automatically when users perform various actions on the platform.

## RFQ (Request for Quotation) Emails

**rfqNotification01.html**
This email is sent to buyers when they submit a quote request. It confirms that their request was received and is being shared with suppliers. The email includes a tracking ID and a button to track incoming quotes.

**rfqCreated02.html**
This is an internal notification sent to the admin team when a new quote is created. It shows both buyer and supplier information. No action is needed - it's just for awareness.

**rfqRecevied03.html**
This email goes to suppliers when a new quote request matches their product category. It includes the request summary, buyer details, and a button to view all open quotes and submit their offer.

## Contact Us Emails

**contactusConfirm01.html**
Sent to users after they submit a contact form. It confirms their inquiry was received and tells them the team will respond within 24 hours. It also shows a summary of their message.

**contactusRequiresAction02.html**
This goes to the internal Pepagora team when someone submits a contact form. It contains the user's details, subject, and message so the team can respond.

**contactusAlert03.html**
An internal alert sent to admins when a contact form is submitted for a supplier. Shows buyer and supplier information along with the message. No action needed - just for awareness.

**contactusApproval04.html**
Sent to users when their domain is approved and verified. It tells them their catalog is now live and ready to share. Includes a checklist of what they can do next and a button to access their catalog.

**contactusUnlock05.html**
Sent when a user successfully purchases and unlocks a lead. It shows the lead's contact details (name, email, phone) and displays remaining credits. Includes a button to view the full lead details.

## PBR (Product Buying Request) Emails

**pbrEmailer01.html**
The main sourcing request email sent to buyers when they submit a product request. This is the most detailed template with sections for request summary, what's happening now, notification updates, and tips to boost response rate. It mentions that 91% of buyers receive quotes within 24 hours.

**pbrNoti02.html**
Sent to suppliers when a new buying request matches their profile. Shows the buyer's information and product details. Encourages suppliers to submit a competitive offer to win the business.

**pbrSupplier03.html**
An internal email for the admin team when a sourcing request needs approval. Shows the requirement summary including price range, quantity, and timeline, along with buyer information. The admin needs to review and approve before it goes to suppliers.

**pbrRejects04.html**
Sent to buyers when their sourcing request is rejected. Explains that the request doesn't meet platform guidelines and gives a brief reason. Provides a link to guidelines and a button to create a new request.

**pbrapproval05.html**
Sent to buyers when their sourcing request is approved. Tells them their request is now being sent to suppliers and explains what happens next - smart matching is active and quotes should arrive within 24-48 hours.

## Onboarding Email

**onBoardingEmailer.html**
An internal notification sent to the admin team when a new buyer or seller joins Pepagora. Shows the new user's information including name, company, location, contact details, and the date they signed up.

## Common Features

All emails share these elements:
- Pepagora logo at the top
- Personalized greeting using the user's first name
- Red accent color for buttons and highlights
- Social media links at the bottom (WhatsApp, Facebook, X, YouTube, Instagram, LinkedIn)
- Unsubscribe and preferences links
- Help and support link
- Copyright notice

The templates are mobile-responsive and will adjust their layout for smaller screens.

## Placeholders

The templates use placeholders that get replaced with real data:
- User's first name
- Product names
- Buyer and supplier names
- Company names
- RFQ IDs
- Domain names
- Lead titles

These placeholders appear as text in brackets like [Product Name] or as system variables like $[UD:FIRST_NAME||]$.
