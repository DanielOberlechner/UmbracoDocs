---
title: ValidateEmailTemplateReplyToAddressChange
description: API reference for ValidateEmailTemplateReplyToAddressChange in Umbraco Commerce
---
## ValidateEmailTemplateReplyToAddressChange

```csharp
public class ValidateEmailTemplateReplyToAddressChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateEmailTemplateReplyToAddressChange

```csharp
public ValidateEmailTemplateReplyToAddressChange(EmailTemplateReadOnly emailTemplate, 
    ChangingValue<string> emailAddress)
```


### Properties

#### EmailTemplate

```csharp
public EmailTemplateReadOnly EmailTemplate { get; }
```


---

#### ReplyToAddress

```csharp
public ChangingValue<string> ReplyToAddress { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
