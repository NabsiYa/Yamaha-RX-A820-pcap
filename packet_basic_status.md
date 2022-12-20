# Details

When you send this packet the receiver will return you with information such as the current volume level.

# Command

```xml
<?xml version="1.0" encoding="utf-8"?>
<YAMAHA_AV cmd="GET">
    <Main_Zone>
        <Basic_Status>GetParam</Basic_Status>
    </Main_Zone>
</YAMAHA_AV>
```

# Response

```xml
<YAMAHA_AV rsp="GET" RC="0">
    <Main_Zone>
        <Basic_Status>
            <Power_Control>
                <Power>Standby</Power>
                <Sleep>Off</Sleep>
            </Power_Control>
            <Volume>
                <Lvl>
                    <Val>-400</Val>
                    <Exp>1</Exp>
                    <Unit>dB</Unit>
                </Lvl>
                <Mute>Off</Mute>
                <Subwoofer_Trim>
                    <Val>0</Val>
                    <Exp>1</Exp>
                    <Unit>dB</Unit>
                </Subwoofer_Trim>
            </Volume>
            <Input>
                <Input_Sel>HDMI6</Input_Sel>
                <Input_Sel_Item_Info>
                    <Param>HDMI6</Param>
                    <RW>RW</RW>
                    <Title>HDMI6</Title>
                    <Icon>
                        <On>/YamahaRemoteControl/Icons/icon004.png</On>
                        <Off></Off>
                    </Icon>
                    <Src_Name></Src_Name>
                    <Src_Number>1</Src_Number>
                </Input_Sel_Item_Info>
            </Input>
            <Surround>
                <Program_Sel>
                    <Current>
                        <Straight>On</Straight>
                        <Enhancer>Off</Enhancer>
                        <Sound_Program>Hall in Munich</Sound_Program>
                    </Current>
                </Program_Sel>
                <_3D_Cinema_DSP>Auto</_3D_Cinema_DSP>
            </Surround>
            <Party_Info>Off</Party_Info>
            <Sound_Video>
                <Tone>
                    <Bass>
                        <Val>-60</Val>
                        <Exp>1</Exp>
                        <Unit>dB</Unit>
                    </Bass>
                    <Treble>
                        <Val>0</Val>
                        <Exp>1</Exp>
                        <Unit>dB</Unit>
                    </Treble>
                </Tone>
                <Pure_Direct>
                    <Mode>Off</Mode>
                </Pure_Direct>
                <HDMI>
                    <Standby_Through_Info>On</Standby_Through_Info>
                    <Output>
                        <OUT_1>On</OUT_1>
                        <OUT_2>On</OUT_2>
                        <OUT_2_Info>On</OUT_2_Info>
                    </Output>
                </HDMI>
                <Adaptive_DRC>Off</Adaptive_DRC>
                <Dialogue_Adjust>
                    <Dialogue_Lift>0</Dialogue_Lift>
                    <Dialogue_Lvl>0</Dialogue_Lvl>
                </Dialogue_Adjust>
            </Sound_Video>
        </Basic_Status>
    </Main_Zone>
</YAMAHA_AV>
```
