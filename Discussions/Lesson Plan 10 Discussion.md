Lee H. Sarduy                                                                                                                                       Chapter 5 - SQL

8/23/2017                                                                                                                                             Pages 161-183

**Homework**

**(Lesson Plan 10)**

1. Declare an enum for military ranks, either officer or enlisted. Name it Ranks. What are the symbols, like Private, PFD, Corporal, or 1stLt, 2ndLt, Capt?
    ```csharp
    enum Enlisted
    {
      REC, PVT, PV2, PFC, SPC, CPL = SPC, SGT,
      SSG, SFC, MSG, FSG = MSG, SGM, CSM = SGM
    }
    ```
1. Using the Ranks enum, assign a rank to yourself or a friend.  
`Enlisted Lee = Enlisted.SPC;`
1. Determine the numeric index of particular ranks, using the Ranks enum.  
**For me, it would be seven had I used the Enlisted Ranks.**
1. How do you select the type of an enum?  
`enum Enlisted : short { REC, ... CSM = SGM}`
1. Are structs stored on the stack or on the heap? What about enums?  
**Structs and enums are both stored on the stack.**
1. Declare a struct named DOD with four branches.  
    ```csharp
    struct DoD
    {
      private string army, airforce, navy, coastguard;
    }
    ```
1. Why can't you create a default constructor for a struct?  
**The reason you can’t declare your own default constructor for a structure is that the compiler always generates one.**
1. What is CIL? What does the CLR do to the CIL?  
**Common Intermediate Language (CIL). The CLR converts the CIL computer language.**