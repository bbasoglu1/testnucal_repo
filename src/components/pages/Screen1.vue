<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="337ed9c1-bfe4-40f2-a4f5-8347c0156bc9" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WDangerAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="danger"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="danger"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="danger" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#dc3545" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545" ncHoverBackgroundColor="#dc3545"
        position="absolute" top="37.14046822742475%" left="28.089130434782607%"
        id="a4b4315a-0555-46e7-aa1e-7fa3d90b31b8"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#f8d7da','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
      <WDarkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="dark"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="dark"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="dark" v-bind:dismissCountDown="5" horizontalHeight=""
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#343a40"
        ncFocusBorderColor="#343a40" ncHoverBorderColor="#343a40" ncClickBackgroundColor="#343a40"
        ncFocusBackgroundColor="#343a40" ncHoverBackgroundColor="#343a40" position="absolute" top="56.20401337792642%"
        left="40.51521739130435%" id="15bfe51a-ca36-4496-9e9e-0b6a99dd067d"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#c6c8ca','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':3}"/>
      <WInfoAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="info"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="info"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="info" v-bind:dismissCountDown="5" horizontalHeight=""
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#2ea2b8"
        ncFocusBorderColor="#2ea2b8" ncHoverBorderColor="#2ea2b8" ncClickBackgroundColor="#2ea2b8"
        ncFocusBackgroundColor="#2ea2b8" ncHoverBackgroundColor="#2ea2b8" position="absolute" top="49.50334448160535%"
        left="16.13695652173913%" id="3f70e973-6fbe-4c88-8dbb-074353c4e860"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#d1ecf1','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':4}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>