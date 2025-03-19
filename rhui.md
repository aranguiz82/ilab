<table>
    <tr>
        <td>Component</td>
        <td>Acronym</td>
        <td>Function</td>
        <td>Alternative</td>
    </tr>
    <tr>
        <td>Red Hat Update Appliance</td>
        <td>RHUA</td>
        <td>Downloads content from the Red Hat content delivery network and stores it on the shared storage</td>
        <td>None</td>
    </tr>
    <tr>
        <td>Content Delivery Server</td>
        <td>CDS</td>
        <td>Provides the yum repositories that clients connect to for the updated packages</td>
        <td>None</td>
    </tr>
    <tr>
        <td>HAProxy</td>
        <td>None</td>
        <td>Provides load balancing across CDS nodes</td>
        <td>Existing load balancing solution</td>
    </tr>
    <tr>
        <td>Shared storage</td>
        <td>None</td>
        <td>Provides shared storage</td>
        <td>Existing storage solution</td>
    </tr>
</table>