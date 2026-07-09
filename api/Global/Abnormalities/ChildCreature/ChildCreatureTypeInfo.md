---
uid: Global.ChildCreatureTypeInfo
canonical_path: /api/Global/Creature/ChildCreatureTypeInfo
---
# Class ChildCreatureTypeInfo
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureTypeInfo : CreatureTypeInfo
```
> This section may have incomplete or incorrect information.
{.is-warning}


Holds basic type information for a [ChildCreatureModel](/api/Global/Abnormalities/ChildCreature/ChildCreatureModel), like risk level and attack type.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureTypeInfo](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo) → ChildCreatureTypeInfo

## Constructors
### ChildCreatureTypeInfo()
```csharp
public ChildCreatureTypeInfo()
```

## Fields
### _attackType
```csharp
public string _attackType
```


#### Field Value
**Type:** System.String

### _riskLevel
```csharp
public string _riskLevel
```


#### Field Value
**Type:** System.String

### attackTypeOpen
```csharp
public int attackTypeOpen
```


#### Field Value
**Type:** System.Int32

### data
```csharp
public ChildCreatureData data
```


#### Field Value
**Type:** Global.ChildCreatureData

### isHasBaseMeta
```csharp
public bool isHasBaseMeta
```


#### Field Value
**Type:** System.Boolean

### riskLevelOpen
```csharp
public int riskLevelOpen
```


#### Field Value
**Type:** System.Int32

## Properties
### attackType
```csharp
public string attackType { get; }
```

#### Property Value
**Type:** System.String

### riskLevel
```csharp
public override string riskLevel { get; }
```

#### Property Value
**Type:** System.String

## Methods
### GetAttackType()
```csharp
public RwbpType GetAttackType()
```


#### Returns
**Type:** Global.RwbpType

### GetRiskLevel()
```csharp
public override RiskLevel GetRiskLevel()
```


#### Returns
**Type:** Global.RiskLevel

## Inherited Members
[stringData](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#stringdata), [intData](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#intdata), [childTypeInfo](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#childtypeinfo), [noDataString](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#nodatastring), [id](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#id), [maxHp](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#maxhp), [creatureWorkType](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#creatureworktype), [creatureKitType](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#creaturekittype), [kitIconSrc](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#kiticonsrc), [workAnim](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#workanim), [workAnimFace](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#workanimface), [feelingStateCubeBounds](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#feelingstatecubebounds), [creatureSpecialDamageTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#creaturespecialdamagetable), [workDamage](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#workdamage), [defenseTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#defensetable), [workCooltime](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#workcooltime), [cubeSpeed](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#cubespeed), [workProbTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#workprobtable), [observeData](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observedata), [equipMakeInfos](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#equipmakeinfos), [observeBonus](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observebonus), [maxWorkCount](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#maxworkcount), [maxProbReductionCounter](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#maxprobreductioncounter), [probReduction](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#probreduction), [animSrc](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#animsrc), [roomReturnSrc](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#roomreturnsrc), [script](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#script), [qliphothMax](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#qliphothmax), [typoTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#typotable), [narrationTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#narrationtable), [soundTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#soundtable), [observe](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observe), [openText](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#opentext), [observeList](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observelist), [nodeInfo](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#nodeinfo), [edgeInfo](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#edgeinfo), [dataTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#datatable), [observeTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observetable), [specialSkillTable](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#specialskilltable), [collectionUsedAgentName](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#collectionusedagentname), [isEscapeAble](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#isescapeable), [MaxObserveLevel](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#maxobservelevel), [speed](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#speed), [_isChildAndHasData](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#ischildandhasdata), [_tempPortrait](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#tempportrait), [activateSpecialSkill](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#activatespecialskill), [tempPortrait](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#tempportrait), [desc](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#desc), [observeRecord](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#observerecord), [skillTriggerCheck](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#skilltriggercheck), [maxObserveModule](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#maxobservemodule), [creatureStaticData](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#creaturestaticdata), [GetRiskLevelEnumToString(RiskLevel)](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#getrisklevelenumtostring-risklevel), [GetRiskLevelStringToEnum(string)](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#getrisklevelstringtoenum-string), [ActivatedSpecialSkill()](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#activatedspecialskill), [GetAgentName(int, out AgentName)](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#getagentname-int-out-agentname), [AddAgentName(int, AgentName)](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#addagentname-int-agentname), [CurrentObserveLevel](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#currentobservelevel), [name](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#name), [collectionName](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#collectionname), [codeId](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#codeid), [riskLevelForce](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#risklevelforce), [portraitSrc](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#portraitsrc), [portraitSrcForcely](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#portraitsrcforcely), [specialSkillName](/api/Global/Abnormalities/CreatureTypeInfo/CreatureTypeInfo#specialskillname), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








