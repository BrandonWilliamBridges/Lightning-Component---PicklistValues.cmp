# Lightning-Component---PicklistValues.cmp
Displays picklist values for a given object and custom picklist field.

Example of use:


  <lightning:select aura:id="propStatus" name="propStatus" label="Status" class="slds-size--1-of-2 slds-p-horizontal_x-small">
  
    <aura:iteration items="{!v.picklistValues}" var="item">
    
      <option value="{!item}">{!item}</option>
      
    </aura:iteration>
    
  </lightning:select>
