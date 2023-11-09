---
title: ValidatePaymentMethodSettingChange
description: API reference for ValidatePaymentMethodSettingChange in Umbraco Commerce
---
## ValidatePaymentMethodSettingChange

```csharp
public class ValidatePaymentMethodSettingChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidatePaymentMethodSettingChange

```csharp
public ValidatePaymentMethodSettingChange(PaymentMethodReadOnly paymentMethod, string alias, 
    ChangingValue<string> value)
```


### Properties

#### Alias

```csharp
public string Alias { get; }
```


---

#### PaymentMethod

```csharp
public PaymentMethodReadOnly PaymentMethod { get; }
```


---

#### Value

```csharp
public ChangingValue<string> Value { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->