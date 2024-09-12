---
title: ValidateEmailTemplateCategoryChange
description: API reference for ValidateEmailTemplateCategoryChange in Umbraco Commerce
---
## ValidateEmailTemplateCategoryChange

```csharp
public class ValidateEmailTemplateCategoryChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateEmailTemplateCategoryChange

```csharp
public ValidateEmailTemplateCategoryChange(EmailTemplateReadOnly emailTemplate, 
    ChangingValue<TemplateCategory> category)
```


### Properties

#### Category

```csharp
public ChangingValue<TemplateCategory> Category { get; }
```


---

#### EmailTemplate

```csharp
public EmailTemplateReadOnly EmailTemplate { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->