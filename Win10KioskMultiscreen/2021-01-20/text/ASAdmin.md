# EventLog path: `Applications and Services Logs/Microsoft/Windows/AssignedAccess/Admin`

    Log Name:      Microsoft-Windows-AssignedAccess/Admin
    Source:        Microsoft-Windows-AssignedAccess
    Date:          2021-01-20 14:57:12
    Event ID:      31000
    Task Category: Applying Assigned Access for current user.
    Level:         Error
    Keywords:      
    User:          WINDEV2012EVAL\KIOSK
    Computer:      WinDev2012Eval
    Description:
    Error The group or resource is not in the correct state to perform the requested operation. applying assigned access for current user, signing out...
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-AssignedAccess" Guid="{8530db6e-51c0-43d6-9d02-a8c2088526cd}" />
        <EventID>31000</EventID>
        <Version>0</Version>
        <Level>2</Level>
        <Task>1002</Task>
        <Opcode>0</Opcode>
        <Keywords>0x4000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.1624580Z" />
        <EventRecordID>6</EventRecordID>
        <Correlation />
        <Execution ProcessID="5852" ThreadID="6096" />
        <Channel>Microsoft-Windows-AssignedAccess/Admin</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1002" />
      </System>
      <EventData>
        <Data Name="ErrorCode">-2147019873</Data>
      </EventData>
    </Event>

    Log Name:      Microsoft-Windows-AssignedAccess/Admin
    Source:        Microsoft-Windows-AssignedAccess
    Date:          2021-01-20 14:57:12
    Event ID:      31002
    Task Category: AssignedAccess OperationStatus messages
    Level:         Error
    Keywords:      
    User:          WINDEV2012EVAL\KIOSK
    Computer:      WinDev2012Eval
    Description:
    TabletMode:Apply:, ErrorCode(0x8007139F)
    Event Xml:
    <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
      <System>
        <Provider Name="Microsoft-Windows-AssignedAccess" Guid="{8530db6e-51c0-43d6-9d02-a8c2088526cd}" />
        <EventID>31002</EventID>
        <Version>0</Version>
        <Level>2</Level>
        <Task>1005</Task>
        <Opcode>0</Opcode>
        <Keywords>0x4000000000000000</Keywords>
        <TimeCreated SystemTime="2021-01-20T13:57:12.1597644Z" />
        <EventRecordID>5</EventRecordID>
        <Correlation />
        <Execution ProcessID="5852" ThreadID="6096" />
        <Channel>Microsoft-Windows-AssignedAccess/Admin</Channel>
        <Computer>WinDev2012Eval</Computer>
        <Security UserID="S-1-5-21-4279892692-2277359461-354179757-1002" />
      </System>
      <EventData>
        <Data Name="Custom">TabletMode:Apply:</Data>
        <Data Name="ErrorCode">0x8007139f</Data>
      </EventData>
    </Event>