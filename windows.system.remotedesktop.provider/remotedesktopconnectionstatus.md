---
-api-id: T:Windows.System.RemoteDesktop.Provider.RemoteDesktopConnectionStatus
-api-type: winrt enum
---

# Windows.System.RemoteDesktop.Provider.RemoteDesktopConnectionStatus

<!--
public enum RemoteDesktopConnectionStatus
-->


## -description

Specifies the connection status of a remote desktop connection.

## -enum-fields

### -field Connecting: 0

The connection is in the process of connecting.

### -field Connected: 1

The connection is active.

### -field UserInputNeeded: 2

User input is needed to complete the connection.

### -field Disconnected: 3

The connection is disconnected.

## -remarks

Remote desktop providers inform the OS of the current status of a remote desktop connection by calling [SetConnectionStatus](xref:Windows.System.RemoteDesktop.Provider.RemoteDesktopConnectionInfo.SetConnectionStatus(Windows.System.RemoteDesktop.Provider.RemoteDesktopConnectionStatus)).

## -see-also

## -examples


