<?xml version="1.0" encoding="UTF-8"?>
<CustomMetadata xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <label>Contact: Soft Credits - Count This Year</label>
    <protected>true</protected>
    <values>
        <field>Active__c</field>
        <value xsi:type="xsd:boolean">true</value>
    </values>
    <values>
        <field>Amount_Field__c</field>
        <value xsi:type="xsd:string">Amount__c</value>
    </values>
    <values>
        <field>Amount_Object__c</field>
        <value xsi:type="xsd:string">Partial_Soft_Credit__c</value>
    </values>
    <values>
        <field>Date_Field__c</field>
        <value xsi:type="xsd:string">CloseDate</value>
    </values>
    <values>
        <field>Date_Object__c</field>
        <value xsi:type="xsd:string">Opportunity</value>
    </values>
    <values>
        <field>Description__c</field>
        <value xsi:type="xsd:string">All Soft Credit Rollups are based on the PartialSoftCredit object even if PSC&apos;s aren&apos;t technically in use. This is because OCR isn&apos;t available as an object to select from. The rollups engine will merge the OCR and PSC data into a single &apos;detail&apos; object source for the rollups</value>
    </values>
    <values>
        <field>Detail_Field__c</field>
        <value xsi:nil="true"/>
    </values>
    <values>
        <field>Detail_Object__c</field>
        <value xsi:type="xsd:string">Partial_Soft_Credit__c</value>
    </values>
    <values>
        <field>Filter_Group__c</field>
        <value xsi:type="xsd:string">ClosedWon_RecordType_not_Membership</value>
    </values>
    <values>
        <field>Integer__c</field>
        <value xsi:type="xsd:double">0.0</value>
    </values>
    <values>
        <field>Operation__c</field>
        <value xsi:type="xsd:string">Count</value>
    </values>
    <values>
        <field>Summary_Field__c</field>
        <value xsi:type="xsd:string">Number_of_Soft_Credits_This_Year__c</value>
    </values>
    <values>
        <field>Summary_Object__c</field>
        <value xsi:type="xsd:string">Contact</value>
    </values>
    <values>
        <field>Use_Fiscal_Year__c</field>
        <value xsi:type="xsd:boolean">false</value>
    </values>
    <values>
        <field>Yearly_Operation_Type__c</field>
        <value xsi:type="xsd:string">Years_Ago</value>
    </values>
</CustomMetadata>