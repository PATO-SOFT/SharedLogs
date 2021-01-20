# EventLog path: `Windows Logs/System`

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:58:06
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff848d-5b27-11eb-bbe4-080027c6da47}, RM: {57ff848c-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:58:06.7812335Z" />
        <EventRecordID>2896</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1012" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff848d-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff848c-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:58:06
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff8476-5b27-11eb-bbe4-080027c6da47}, RM: {57ff8475-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:58:06.7811238Z" />
        <EventRecordID>2895</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1012" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff8476-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff8475-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Service Control Manager
    Date:          2021-01-20 14:57:59
    Event ID:      7040
    Task Category: None
    Level:         Information
    Keywords:      Classic
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The start type of the Background Intelligent Transfer Service service was changed from demand start to auto start.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Service Control Manager" Guid="{555908d1-a6d7-4695-8e1e-26931d2012f4}" EventSourceName="Service Control Manager" />
        <EventID Qualifiers="16384">7040</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8080000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:59.3427786Z" />
        <EventRecordID>2894</EventRecordID>
        <Correlation />
        <Execution ProcessID="772" ThreadID="4256" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="param1">Background Intelligent Transfer Service</Data>
        <Data Name="param2">demand start</Data>
        <Data Name="param3">auto start</Data>
        <Data Name="param4">BITS</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-WindowsUpdateClient
    Date:          2021-01-20 14:57:52
    Event ID:      19
    Task Category: Windows Update Agent
    Level:         Information
    Keywords:      Success,Installation
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Installation Successful: Windows successfully installed the following update: Security Intelligence Update for Microsoft Defender Antivirus - KB2267602 (Version 1.329.2528.0)
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-WindowsUpdateClient" Guid="{945a8954-c147-4acd-923f-40c45405a658}" />
        <EventID>19</EventID>
        <Version>1</Version>
        <Level>4</Level>
        <Task>1</Task>
        <Opcode>13</Opcode>
        <Keywords>0x8000000000000018</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:52.6827027Z" />
        <EventRecordID>2893</EventRecordID>
        <Correlation />
        <Execution ProcessID="3148" ThreadID="3440" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="updateTitle">Security Intelligence Update for Microsoft Defender Antivirus - KB2267602 (Version 1.329.2528.0)</Data>
        <Data Name="updateGuid">{677fef73-98b2-4acb-92ec-a33238fc495e}</Data>
        <Data Name="updateRevisionNumber">200</Data>
        <Data Name="serviceGuid">{9482f4b4-e343-43b6-b170-9a65bc822c77}</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:49
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff8476-5b27-11eb-bbe4-080027c6da47}, RM: {57ff8475-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:49.2781629Z" />
        <EventRecordID>2892</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1116" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff8476-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff8475-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:49
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff846f-5b27-11eb-bbe4-080027c6da47}, RM: {57ff846e-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:49.2780009Z" />
        <EventRecordID>2891</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1116" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff846f-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff846e-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:48
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff846f-5b27-11eb-bbe4-080027c6da47}, RM: {57ff846e-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:48.7533815Z" />
        <EventRecordID>2890</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="816" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff846f-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff846e-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:48
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff8467-5b27-11eb-bbe4-080027c6da47}, RM: {57ff8466-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:48.7532446Z" />
        <EventRecordID>2889</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="816" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff8467-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff8466-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:47
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff8467-5b27-11eb-bbe4-080027c6da47}, RM: {57ff8466-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:47.6741126Z" />
        <EventRecordID>2888</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1008" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff8467-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff8466-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:47
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff845d-5b27-11eb-bbe4-080027c6da47}, RM: {57ff845c-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:47.6739557Z" />
        <EventRecordID>2887</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1008" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff845d-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff845c-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:47
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff845d-5b27-11eb-bbe4-080027c6da47}, RM: {57ff845c-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:47.1328930Z" />
        <EventRecordID>2886</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1008" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff845d-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff845c-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:47
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\User
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff841f-5b27-11eb-bbe4-080027c6da47}, RM: {57ff841e-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:47.1327111Z" />
        <EventRecordID>2885</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1008" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1001" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff841f-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff841e-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Winlogon
    Date:          2021-01-20 14:57:44
    Event ID:      7001
    Task Category: (1101)
    Level:         Information
    Keywords:      (35184372088832)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    User Logon Notification for Customer Experience Improvement Program
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Winlogon" Guid="{dbe9b383-7cf3-4331-91cc-a3cb16a3b538}" />
        <EventID>7001</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>1101</Task>
        <Opcode>0</Opcode>
        <Keywords>0x2000200000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:44.2451680Z" />
        <EventRecordID>2884</EventRecordID>
        <Correlation />
        <Execution ProcessID="7024" ThreadID="7120" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="TSId">2</Data>
        <Data Name="UserSid">S-1-5-21-4279892692-2277359461-354179757-1001</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-WindowsUpdateClient
    Date:          2021-01-20 14:57:41
    Event ID:      43
    Task Category: Windows Update Agent
    Level:         Information
    Keywords:      Started,Installation
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Installation Started: Windows has started installing the following update: Security Intelligence Update for Microsoft Defender Antivirus - KB2267602 (Version 1.329.2528.0)
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-WindowsUpdateClient" Guid="{945a8954-c147-4acd-923f-40c45405a658}" />
        <EventID>43</EventID>
        <Version>1</Version>
        <Level>4</Level>
        <Task>1</Task>
        <Opcode>13</Opcode>
        <Keywords>0x8000000000002008</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:41.4527399Z" />
        <EventRecordID>2883</EventRecordID>
        <Correlation />
        <Execution ProcessID="3148" ThreadID="800" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="updateTitle">Security Intelligence Update for Microsoft Defender Antivirus - KB2267602 (Version 1.329.2528.0)</Data>
        <Data Name="updateGuid">{677fef73-98b2-4acb-92ec-a33238fc495e}</Data>
        <Data Name="updateRevisionNumber">200</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-WindowsUpdateClient
    Date:          2021-01-20 14:57:41
    Event ID:      44
    Task Category: Windows Update Agent
    Level:         Information
    Keywords:      Started,Download
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Windows Update started downloading an update.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-WindowsUpdateClient" Guid="{945a8954-c147-4acd-923f-40c45405a658}" />
        <EventID>44</EventID>
        <Version>1</Version>
        <Level>4</Level>
        <Task>1</Task>
        <Opcode>12</Opcode>
        <Keywords>0x8000000000002004</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:41.4523499Z" />
        <EventRecordID>2882</EventRecordID>
        <Correlation />
        <Execution ProcessID="3148" ThreadID="800" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="updateTitle">Security Intelligence Update for Microsoft Defender Antivirus - KB2267602 (Version 1.329.2528.0)</Data>
        <Data Name="updateGuid">{677fef73-98b2-4acb-92ec-a33238fc495e}</Data>
        <Data Name="updateRevisionNumber">200</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Winlogon
    Date:          2021-01-20 14:57:12
    Event ID:      7002
    Task Category: (1102)
    Level:         Information
    Keywords:      (35184372088832)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    User Logoff Notification for Customer Experience Improvement Program
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Winlogon" Guid="{dbe9b383-7cf3-4331-91cc-a3cb16a3b538}" />
        <EventID>7002</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>1102</Task>
        <Opcode>0</Opcode>
        <Keywords>0x2000200000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.7143751Z" />
        <EventRecordID>2881</EventRecordID>
        <Correlation />
        <Execution ProcessID="732" ThreadID="780" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="TSId">1</Data>
        <Data Name="UserSid">S-1-5-21-4279892692-2277359461-354179757-1002</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-DistributedCOM
    Date:          2021-01-20 14:57:12
    Event ID:      10010
    Task Category: None
    Level:         Error
    Keywords:      Classic
    User:          WINDEV2012EVAL\KIOSK
    Computer:      WinDev2012Eval
    Description:
    The server Microsoft.Windows.StartMenuExperienceHost_10.0.19041.610_neutral_neutral_cw5n1h2txyewy!App did not register with DCOM within the required timeout.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-DistributedCOM" Guid="{1B562E86-B7AA-4131-BADC-B6F3A001407E}" EventSourceName="DCOM" />
        <EventID Qualifiers="0">10010</EventID>
        <Version>0</Version>
        <Level>2</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8080000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.5043709Z" />
        <EventRecordID>2880</EventRecordID>
        <Correlation ActivityID="{a84a3526-0a66-436e-92fd-193b8977515d}" />
        <Execution ProcessID="84" ThreadID="1644" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1002" />
      </System>
      <EventData>
        <Data Name="param1">Microsoft.Windows.StartMenuExperienceHost_10.0.19041.610_neutral_neutral_cw5n1h2txyewy!App</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:12
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\KIOSK
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {57ff841f-5b27-11eb-bbe4-080027c6da47}, RM: {57ff841e-5b27-11eb-bbe4-080027c6da47}) finished with result=0xC0000022 (Internal code=7).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.2321381Z" />
        <EventRecordID>2879</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1012" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1002" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{57ff841f-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="RmId">{57ff841e-5b27-11eb-bbe4-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">7</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:12
    Event ID:      11
    Task Category: None
    Level:         Information
    Keywords:      
    User:          WINDEV2012EVAL\KIOSK
    Computer:      WinDev2012Eval
    Description:
    TxR init phase for hive \SystemRoot\System32\AppLocker\AppCache.dat (TM: {47625167-5a78-11eb-bbe3-080027c6da47}, RM: {47625166-5a78-11eb-bbe3-080027c6da47}) finished with result=0xC0000022 (Internal code=0).
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>11</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.2318488Z" />
        <EventRecordID>2878</EventRecordID>
        <Correlation />
        <Execution ProcessID="912" ThreadID="1012" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1002" />
      </System>
      <EventData>
        <Data Name="ExtraStringLength">43</Data>
        <Data Name="ExtraString">\SystemRoot\System32\AppLocker\AppCache.dat</Data>
        <Data Name="TmId">{47625167-5a78-11eb-bbe3-080027c6da47}</Data>
        <Data Name="RmId">{47625166-5a78-11eb-bbe3-080027c6da47}</Data>
        <Data Name="Status">0xc0000022</Data>
        <Data Name="InternalCode">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Winlogon
    Date:          2021-01-20 14:57:08
    Event ID:      7001
    Task Category: (1101)
    Level:         Information
    Keywords:      (35184372088832)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    User Logon Notification for Customer Experience Improvement Program
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Winlogon" Guid="{dbe9b383-7cf3-4331-91cc-a3cb16a3b538}" />
        <EventID>7001</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>1101</Task>
        <Opcode>0</Opcode>
        <Keywords>0x2000200000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:08.3774362Z" />
        <EventRecordID>2877</EventRecordID>
        <Correlation />
        <Execution ProcessID="732" ThreadID="780" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="TSId">1</Data>
        <Data Name="UserSid">S-1-5-21-4279892692-2277359461-354179757-1002</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Service Control Manager
    Date:          2021-01-20 14:57:07
    Event ID:      7026
    Task Category: None
    Level:         Information
    Keywords:      Classic
    User:          N/A
    Computer:      WinDev2012Eval
    Description:
    The following boot-start or system-start driver(s) did not load: 
    dam
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Service Control Manager" Guid="{555908d1-a6d7-4695-8e1e-26931d2012f4}" EventSourceName="Service Control Manager" />
        <EventID Qualifiers="49152">7026</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8080000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:07.0851804Z" />
        <EventRecordID>2876</EventRecordID>
        <Correlation />
        <Execution ProcessID="772" ThreadID="776" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security />
      </System>
      <EventData>
        <Data Name="param1">
    dam</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Hyper-V-VmSwitch
    Date:          2021-01-20 14:57:06
    Event ID:      277
    Task Category: None
    Level:         Information
    Keywords:      (128)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    vmswitch.sys build 19041.amd64.vb_release_svc_prod1, debug false, official true, 1 1
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Hyper-V-VmSwitch" Guid="{67dc0d66-3695-47c0-9642-33f76f7bd7ad}" />
        <EventID>277</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000080</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.6405984Z" />
        <EventRecordID>2875</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="380" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="BuildNumber">19041</Data>
        <Data Name="BuildArch">amd64</Data>
        <Data Name="BuildBranch">vb_release_svc_prod1</Data>
        <Data Name="Debug">false</Data>
        <Data Name="Official">true</Data>
        <Data Name="Date">1</Data>
        <Data Name="Time">1</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-DHCPv6-Client
    Date:          2021-01-20 14:57:06
    Event ID:      51046
    Task Category: Service State Event
    Level:         Information
    Keywords:      
    User:          LOCAL SERVICE
    Computer:      WinDev2012Eval
    Description:
    DHCPv6 client service is started
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-DHCPv6-Client" Guid="{6a1f2b00-6a90-4c38-95a5-5cab3b056778}" />
        <EventID>51046</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>4</Task>
        <Opcode>62</Opcode>
        <Keywords>0x2000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2773036Z" />
        <EventRecordID>2874</EventRecordID>
        <Correlation />
        <Execution ProcessID="1968" ThreadID="1516" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-19" />
      </System>
      <EventData>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Dhcp-Client
    Date:          2021-01-20 14:57:06
    Event ID:      50103
    Task Category: Service State Event
    Level:         Information
    Keywords:      
    User:          LOCAL SERVICE
    Computer:      WinDev2012Eval
    Description:
    DHCPv4 client registered for shutdown notification
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Dhcp-Client" Guid="{15a7a4f8-0072-4eab-abad-f98a4d666aed}" />
        <EventID>50103</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>4</Task>
        <Opcode>129</Opcode>
        <Keywords>0x2000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2613052Z" />
        <EventRecordID>2873</EventRecordID>
        <Correlation />
        <Execution ProcessID="1968" ThreadID="2028" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-19" />
      </System>
      <EventData>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Dhcp-Client
    Date:          2021-01-20 14:57:06
    Event ID:      50036
    Task Category: Service State Event
    Level:         Information
    Keywords:      
    User:          LOCAL SERVICE
    Computer:      WinDev2012Eval
    Description:
    DHCPv4 client service is started
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Dhcp-Client" Guid="{15a7a4f8-0072-4eab-abad-f98a4d666aed}" />
        <EventID>50036</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>4</Task>
        <Opcode>68</Opcode>
        <Keywords>0x2000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2612020Z" />
        <EventRecordID>2872</EventRecordID>
        <Correlation />
        <Execution ProcessID="1968" ThreadID="2028" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-19" />
      </System>
      <EventData>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'bindflt' (10.0, ‎2018‎-‎04‎-‎05T01:18:59.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2566051Z" />
        <EventRecordID>2871</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">7</Data>
        <Data Name="DeviceName">bindflt</Data>
        <Data Name="DeviceTime">2018-04-05T01:18:59.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'storqosflt' (10.0, ‎2007‎-‎04‎-‎09T19:08:30.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2423819Z" />
        <EventRecordID>2870</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">10</Data>
        <Data Name="DeviceName">storqosflt</Data>
        <Data Name="DeviceTime">2007-04-09T19:08:30.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'CldFlt' (10.0, ‎1993‎-‎07‎-‎09T23:45:53.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2286671Z" />
        <EventRecordID>2869</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">6</Data>
        <Data Name="DeviceName">CldFlt</Data>
        <Data Name="DeviceTime">1993-07-09T23:45:53.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      1
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'CldFlt' (Version 10.0, ‎1993‎-‎07‎-‎09T23:45:53.000000000Z) unloaded successfully.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>1</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2285106Z" />
        <EventRecordID>2868</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">6</Data>
        <Data Name="DeviceName">CldFlt</Data>
        <Data Name="DeviceTime">1993-07-09T23:45:53.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'CldFlt' (10.0, ‎1993‎-‎07‎-‎09T23:45:53.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2284942Z" />
        <EventRecordID>2867</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">6</Data>
        <Data Name="DeviceName">CldFlt</Data>
        <Data Name="DeviceTime">1993-07-09T23:45:53.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'luafv' (10.0, ‎1990‎-‎03‎-‎14T03:20:25.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.2078501Z" />
        <EventRecordID>2866</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="368" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">5</Data>
        <Data Name="DeviceName">luafv</Data>
        <Data Name="DeviceTime">1990-03-14T03:20:25.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:57:06
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'wcifs' (10.0, ‎2027‎-‎02‎-‎01T03:32:49.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:06.1886369Z" />
        <EventRecordID>2865</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="32" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">5</Data>
        <Data Name="DeviceName">wcifs</Data>
        <Data Name="DeviceTime">2027-02-01T03:32:49.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Directory-Services-SAM
    Date:          2021-01-20 14:57:05
    Event ID:      16977
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The domain is configured with the following minimum password length-related settings.

    MinimumPasswordLength: 0

    RelaxMinimumPasswordLengthLimits: 0

    MinimumPasswordLengthAudit: -1

    For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.

    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Directory-Services-SAM" Guid="{0d4fdc09-8c27-494a-bda0-505e4fd8adae}" />
        <EventID>16977</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:05.8377055Z" />
        <EventRecordID>2864</EventRecordID>
        <Correlation ActivityID="{1a0034cb-ef34-0005-0535-001a34efd601}" />
        <Execution ProcessID="788" ThreadID="792" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData Name="SAMMSG_MINPWDLEN_SETTINGS_IN_EFFECT">
        <Data Name="MinimumPasswordLength">0</Data>
        <Data Name="RelaxMinimumPasswordLengthLimits">0</Data>
        <Data Name="MinimumPasswordLengthAudit">-1</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Directory-Services-SAM
    Date:          2021-01-20 14:57:05
    Event ID:      16962
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Remote calls to the SAM database are being restricted using the default security descriptor: O:SYG:SYD:(A;;RC;;;BA).
    For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Directory-Services-SAM" Guid="{0d4fdc09-8c27-494a-bda0-505e4fd8adae}" />
        <EventID>16962</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:05.8298954Z" />
        <EventRecordID>2863</EventRecordID>
        <Correlation ActivityID="{1a0034cb-ef34-0005-0535-001a34efd601}" />
        <Execution ProcessID="788" ThreadID="792" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData Name="SAMMSG_RESTRICT_REMOTE_SAM_DEFAULT_SD">
        <Data Name="Default SD String:">O:SYG:SYD:(A;;RC;;;BA)</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Wininit
    Date:          2021-01-20 14:57:05
    Event ID:      14
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Credential Guard configuration: 0x0, 0
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Wininit" Guid="{206f6dea-d3c5-4d10-bc72-989f03c8b84b}" />
        <EventID>14</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x4000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:05.6712079Z" />
        <EventRecordID>2862</EventRecordID>
        <Correlation />
        <Execution ProcessID="624" ThreadID="628" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Config">0</Data>
        <Data Name="IsTestConfig">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:57:05
    Event ID:      24
    Task Category: (11)
    Level:         Information
    Keywords:      Time
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The time zone information was refreshed with exit reason 0. Current time zone bias is -60.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>24</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>11</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000010</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:05.3299290Z" />
        <EventRecordID>2861</EventRecordID>
        <Correlation />
        <Execution ProcessID="140" ThreadID="524" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="ExitReason">0</Data>
        <Data Name="CurrentBias">-60</Data>
        <Data Name="CurrentTimeZoneID">1</Data>
        <Data Name="TimeZoneInfoCacheUpdated">0</Data>
        <Data Name="FirstRefresh">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Ntfs
    Date:          2021-01-20 14:57:04
    Event ID:      98
    Task Category: None
    Level:         Information
    Keywords:      (2)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Volume \\?\Volume{3676a1ae-0000-0000-0000-c0a01f000000} (\Device\HarddiskVolume3) is healthy.  No action is needed.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Ntfs" Guid="{3ff37a1c-a68d-4d6e-8c9b-f79e8b16c482}" />
        <EventID>98</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000002</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:04.4692991Z" />
        <EventRecordID>2860</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="196" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="DriveName">\\?\Volume{3676a1ae-0000-0000-0000-c0a01f000000}</Data>
        <Data Name="DeviceName">\Device\HarddiskVolume3</Data>
        <Data Name="CorruptionActionState">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 7 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2945551Z" />
        <EventRecordID>2859</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">7</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 6 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2938044Z" />
        <EventRecordID>2858</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">6</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 5 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2932046Z" />
        <EventRecordID>2857</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">5</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 4 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2924456Z" />
        <EventRecordID>2856</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">4</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 3 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2915429Z" />
        <EventRecordID>2855</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">3</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 2 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2909039Z" />
        <EventRecordID>2854</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">2</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 1 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2903091Z" />
        <EventRecordID>2853</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">1</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Processor-Power
    Date:          2021-01-20 14:56:59
    Event ID:      55
    Task Category: (47)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Processor 0 in group 0 exposes the following power management capabilities:

    Idle state type: ACPI Idle (C) States (1 state(s))

    Performance state type: None
    Nominal Frequency (MHz): 2994
    Maximum performance percentage: 100
    Minimum performance percentage: 100
    Minimum throttle percentage: 100
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Processor-Power" Guid="{0f67e49f-fe51-4e9f-b490-6f2948cc6027}" />
        <EventID>55</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>47</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:59.2893107Z" />
        <EventRecordID>2852</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Group">0</Data>
        <Data Name="Number">0</Data>
        <Data Name="IdleStateCount">1</Data>
        <Data Name="IdleImplementation">1</Data>
        <Data Name="NominalFrequency">2994</Data>
        <Data Name="MaximumPerformancePercent">100</Data>
        <Data Name="MinimumPerformancePercent">100</Data>
        <Data Name="MinimumThrottlePercent">100</Data>
        <Data Name="PerformanceImplementation">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-PnP
    Date:          2021-01-20 14:56:58
    Event ID:      219
    Task Category: (212)
    Level:         Warning
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The driver \Driver\vmbusr failed to load for the device ROOT\VMBus\0000.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-PnP" Guid="{9c205a39-1250-487d-abd7-e831c6290539}" />
        <EventID>219</EventID>
        <Version>0</Version>
        <Level>3</Level>
        <Task>212</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:58.3151633Z" />
        <EventRecordID>2851</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="392" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="DriverNameLength">15</Data>
        <Data Name="DriverName">ROOT\VMBus\0000</Data>
        <Data Name="Status">3221226341</Data>
        <Data Name="FailureNameLength">14</Data>
        <Data Name="FailureName">\Driver\vmbusr</Data>
        <Data Name="Version">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Power
    Date:          2021-01-20 14:56:58
    Event ID:      172
    Task Category: (203)
    Level:         Information
    Keywords:      (1024),(4)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Connectivity state in standby: Disconnected, Reason: NIC compliance
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Power" Guid="{331c3b3a-2005-44c2-ac5e-77220c37d6b4}" />
        <EventID>172</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>203</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000404</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:58.2566623Z" />
        <EventRecordID>2850</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="368" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="State">2</Data>
        <Data Name="Reason">6</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Ntfs
    Date:          2021-01-20 14:56:58
    Event ID:      98
    Task Category: None
    Level:         Information
    Keywords:      (2)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Volume \\?\Volume{3676a1ae-0000-0000-0000-100000000000} (\Device\HarddiskVolume1) is healthy.  No action is needed.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Ntfs" Guid="{3ff37a1c-a68d-4d6e-8c9b-f79e8b16c482}" />
        <EventID>98</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000002</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:58.0225294Z" />
        <EventRecordID>2849</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="DriveName">\\?\Volume{3676a1ae-0000-0000-0000-100000000000}</Data>
        <Data Name="DeviceName">\Device\HarddiskVolume1</Data>
        <Data Name="CorruptionActionState">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:56:57
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'npsvctrig' (10.0, ‎2025‎-‎01‎-‎06T03:41:12.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:57.8270754Z" />
        <EventRecordID>2848</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">9</Data>
        <Data Name="DeviceName">npsvctrig</Data>
        <Data Name="DeviceTime">2025-01-06T03:41:12.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        VfpExt
    Date:          2021-01-20 14:56:57
    Event ID:      7036
    Task Category: None
    Level:         Information
    Keywords:      Classic
    User:          N/A
    Computer:      WinDev2012Eval
    Description:
    The  service entered the Driver load complete state.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="VfpExt" />
        <EventID Qualifiers="16384">7036</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x80000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:57.4374649Z" />
        <EventRecordID>2847</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security />
      </System>
      <EventData>
        <Data>
        </Data>
        <Data>Driver load complete</Data>
        <Binary>0000040002003000000000007C1B004000000000000000000000000000000000000000000000000054000600</Binary>
      </EventData>
    </Event>

    Log Name:      System
    Source:        VfpExt
    Date:          2021-01-20 14:56:57
    Event ID:      7036
    Task Category: None
    Level:         Information
    Keywords:      Classic
    User:          N/A
    Computer:      WinDev2012Eval
    Description:
    The  service entered the Driver load start state.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="VfpExt" />
        <EventID Qualifiers="16384">7036</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x80000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:57.4374649Z" />
        <EventRecordID>2846</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="376" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security />
      </System>
      <EventData>
        <Data>
        </Data>
        <Data>Driver load start</Data>
        <Binary>0000000002002C00000000007C1B0040000000000000000000000000000000000000000000000000</Binary>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:56:56
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'FileCrypt' (10.0, ‎2002‎-‎03‎-‎01T12:12:42.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:56.7565848Z" />
        <EventRecordID>2845</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">9</Data>
        <Data Name="DeviceName">FileCrypt</Data>
        <Data Name="DeviceTime">2002-03-01T12:12:42.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Ntfs
    Date:          2021-01-20 14:56:55
    Event ID:      98
    Task Category: None
    Level:         Information
    Keywords:      (2)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Volume C: (\Device\HarddiskVolume2) is healthy.  No action is needed.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Ntfs" Guid="{3ff37a1c-a68d-4d6e-8c9b-f79e8b16c482}" />
        <EventID>98</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000002</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:55.0834341Z" />
        <EventRecordID>2844</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="368" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="DriveName">C:</Data>
        <Data Name="DeviceName">\Device\HarddiskVolume2</Data>
        <Data Name="CorruptionActionState">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:56:51
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'WdFilter' (10.0, ‎2057‎-‎03‎-‎10T17:40:27.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.9458427Z" />
        <EventRecordID>2843</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">8</Data>
        <Data Name="DeviceName">WdFilter</Data>
        <Data Name="DeviceTime">2057-03-10T17:40:27.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:56:51
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'Wof' (10.0, ‎2029‎-‎03‎-‎19T09:57:47.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.9412461Z" />
        <EventRecordID>2842</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">3</Data>
        <Data Name="DeviceName">Wof</Data>
        <Data Name="DeviceTime">2029-03-19T09:57:47.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-FilterManager
    Date:          2021-01-20 14:56:51
    Event ID:      6
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    File System Filter 'FileInfo' (10.0, ‎2062‎-‎12‎-‎23T06:21:06.000000000Z) has successfully loaded and registered with Filter Manager.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-FilterManager" Guid="{f3c5e28e-63f6-49c7-a204-e48a1bc4b09d}" />
        <EventID>6</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.9406257Z" />
        <EventRecordID>2841</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="FinalStatus">0x0</Data>
        <Data Name="DeviceVersionMajor">10</Data>
        <Data Name="DeviceVersionMinor">0</Data>
        <Data Name="DeviceNameLength">8</Data>
        <Data Name="DeviceName">FileInfo</Data>
        <Data Name="DeviceTime">2062-12-23T06:21:06.0000000Z</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-HAL
    Date:          2021-01-20 14:56:51
    Event ID:      16
    Task Category: None
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The iommu fault reporting has been initialized.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-HAL" Guid="{63d1e632-95cc-4443-9312-af927761d52a}" />
        <EventID>16</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.5092072Z" />
        <EventRecordID>2840</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:56:51
    Event ID:      20
    Task Category: (6)
    Level:         Information
    Keywords:      Time
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The leap second configuration has been updated.
    Reason: Leap second data initialized from registry during boot
    Leap seconds enabled: true
    New leap second count: 0
    Old leap second count: 0
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>20</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>6</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000010</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3530862Z" />
        <EventRecordID>2839</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="UpdateReason">0</Data>
        <Data Name="EnabledNew">true</Data>
        <Data Name="CountNew">0</Data>
        <Data Name="CountOld">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      32
    Task Category: (58)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The bootmgr spent 0 ms waiting for user input.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>32</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>58</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3303424Z" />
        <EventRecordID>2838</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="BitlockerUserInputTime">0</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      18
    Task Category: (57)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    There are 0x1 boot options on this system.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>18</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>57</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3303106Z" />
        <EventRecordID>2837</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="EntryCount">1</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      27
    Task Category: (33)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The boot type was 0x0.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>27</EventID>
        <Version>1</Version>
        <Level>4</Level>
        <Task>33</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3302499Z" />
        <EventRecordID>2836</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="BootType">0</Data>
        <Data Name="LoadOptions"> NOEXECUTE=OPTIN  HYPERVISORLAUNCHTYPE=AUTO</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      25
    Task Category: (32)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The boot menu policy was 0x1.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>25</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>32</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3302495Z" />
        <EventRecordID>2835</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="BootMenuPolicy">1</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      124
    Task Category: (80)
    Level:         Error
    Keywords:      (70368744177664),(8796093022208)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The virtualization-based security enablement policy check at phase 0 failed with status: The request is not supported.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>124</EventID>
        <Version>0</Version>
        <Level>2</Level>
        <Task>80</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000480000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3302490Z" />
        <EventRecordID>2834</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Phase">0</Data>
        <Data Name="Status">3221225659</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Hyper-V-Hypervisor
    Date:          2021-01-20 14:56:51
    Event ID:      59
    Task Category: None
    Level:         Error
    Keywords:      (70368744177664)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Hypervisor launch failed; Second Level Address Translation is required to launch the hypervisor.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Hyper-V-Hypervisor" Guid="{52fc89f8-995e-434c-a91e-199986449890}" />
        <EventID>59</EventID>
        <Version>0</Version>
        <Level>2</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000400000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3301848Z" />
        <EventRecordID>2833</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      20
    Task Category: (31)
    Level:         Information
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The last shutdown's success status was true. The last boot's success status was true.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>20</EventID>
        <Version>1</Version>
        <Level>4</Level>
        <Task>31</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3301405Z" />
        <EventRecordID>2832</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="LastShutdownGood">true</Data>
        <Data Name="LastBootGood">true</Data>
        <Data Name="LastBootId">27</Data>
        <Data Name="BootStatusPolicy">2</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-Boot
    Date:          2021-01-20 14:56:51
    Event ID:      156
    Task Category: None
    Level:         Warning
    Keywords:      
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    Virtualization-based security (policies: VBS Enabled,VSM Required,Boot Chain Signer Soft Enforced) is disabled due to VBS initialization failure with status: The request is not supported.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-Boot" Guid="{15ca44ff-4d7a-4baa-bba5-0998955e531e}" />
        <EventID>156</EventID>
        <Version>0</Version>
        <Level>3</Level>
        <Task>0</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3300332Z" />
        <EventRecordID>2831</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="Status">3221225659</Data>
        <Data Name="EnableDisableReason">6</Data>
        <Data Name="VsmPolicy">515</Data>
      </EventData>
    </Event>

    Log Name:      System
    Source:        Microsoft-Windows-Kernel-General
    Date:          2021-01-20 14:56:51
    Event ID:      12
    Task Category: (1)
    Level:         Information
    Keywords:      (128)
    User:          SYSTEM
    Computer:      WinDev2012Eval
    Description:
    The operating system started at system time ‎2021‎-‎01‎-‎20T13:56:49.500000000Z.
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-Kernel-General" Guid="{a68ca8b7-004f-d7b6-a698-07e2de0f1f5d}" />
        <EventID>12</EventID>
        <Version>0</Version>
        <Level>4</Level>
        <Task>1</Task>
        <Opcode>0</Opcode>
        <Keywords>0x8000000000000080</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:56:51.3299376Z" />
        <EventRecordID>2830</EventRecordID>
        <Correlation />
        <Execution ProcessID="4" ThreadID="8" />
        <Channel>System</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-18" />
      </System>
      <EventData>
        <Data Name="MajorVersion">10</Data>
        <Data Name="MinorVersion">0</Data>
        <Data Name="BuildVersion">19041</Data>
        <Data Name="QfeVersion">746</Data>
        <Data Name="ServiceVersion">0</Data>
        <Data Name="BootMode">0</Data>
        <Data Name="StartTime">2021-01-20T13:56:49.5000000Z</Data>
      </EventData>
    </Event>