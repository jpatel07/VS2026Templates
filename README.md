
```md
# Problem Solving Visual Studio Template (VS 2026)

A Visual Studio 2026 solution template for coding problems and interview practice.  
It creates a ready-to-run **class library + xUnit test project** with starter code.

---

## What It Creates

If you enter `TwoSum` as the project name:

```

ProblemTwoSum.sln
├─ TwoSum
│  ├─ TwoSum.cs
│  └─ TwoSum.csproj
└─ TwoSum.Tests
├─ TwoSumTests.cs
└─ TwoSum.Tests.csproj

````

### Library (`TwoSum`)
```csharp
public bool Foo(int val)
{
    throw new NotImplementedException("Not implemented.");
}
````

### Tests (`TwoSum.Tests`)

```csharp
[Fact]
public void Foo_InputIs1_ThrowsNotImplemented()
{
    var sut = new TwoSum();
    Assert.Throws<NotImplementedException>(() => sut.Foo(1));
}
```

Build and run tests immediately after creation.

---

## Installation (Visual Studio 2026)

1. Download `ProblemSolvingSolutionTemplate_VSExportStyle.zip`
2. **Do not unzip**
3. Copy to:

   ```
   C:\Users\<your-username>\OneDrive\Documents\Visual Studio 18\Templates\ProjectTemplates
   ```
4. Close Visual Studio
5. Open **Developer Command Prompt for VS 2026** and run:

   ```bat
   devenv /installvstemplates
   ```
6. Reopen Visual Studio

---

## Usage

1. **File → New → Project**
2. Search for **Problem Solving Solution**
3. Enter your problem name (e.g. `TwoSum`)
4. Click **Create**

---

## Requirements

* Visual Studio 2026 (VS 18)
* .NET 8 SDK

---

## License

MIT

```

---

If you want an **ultra-minimal** version (≈10 lines) or a **screenshot-friendly** README, I can do that too.
```
