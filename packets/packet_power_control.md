# Details

This packet allows you to turn the machine on and off by changing `value_here` to either `On` or `Off`.

# Command

```xml
<?xml version="1.0" encoding="utf-8"?>
<YAMAHA_AV cmd="PUT">
    <Main_Zone>
        <Power_Control>
            <Power>value_here</Power>
        </Power_Control>
    </Main_Zone>
</YAMAHA_AV>
```

# Response

```xml
<YAMAHA_AV rsp="PUT" RC="0">
    <Main_Zone>
        <Power_Control>
            <Power></Power>
        </Power_Control>
    </Main_Zone>
</YAMAHA_AV>
```
