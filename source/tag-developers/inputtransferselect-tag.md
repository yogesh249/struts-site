---
layout: default
title: Tag Developers Guide
---

# inputtransferselect

__Description__



{% comment %}start snippet id=javadoc|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}
<p> <p>
 Create a input transfer select component which is basically an text input
 and  <select ...> tag with buttons in the middle of them allowing text
 to be added to the transfer select. Will auto-select all its
 elements upon its containing form submission.
 </p>
</p>
{% comment %}end snippet id=javadoc|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}

{% comment %}start snippet id=notice|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}
<p> <p>
 NOTE: The id and doubleId need not be supplied as they will generated provided
 that the inputtransferselect tag is being used in a form tag. The generated id
 and doubleId will be <form_id>_<inputtransferselect_doubleName> and
 <form_id>_<inputtransferselect_doubleName> respectively.
 </p>
</p>
{% comment %}end snippet id=notice|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}

__Parameters__



{% comment %}start snippet id=tagattributes|javadoc=false|url=struts2-tags/inputtransferselect.html {% endcomment %}
<p>		<table width="100%">

			<tr>

				<td colspan="6"><h4>Dynamic Attributes Allowed:</h4> false</td>

			</tr>

			<tr>

				<td colspan="6">&nbsp;</td>

			</tr>

			<tr>

				<th align="left" valign="top"><h4>Name</h4></th>

				<th align="left" valign="top"><h4>Required</h4></th>

				<th align="left" valign="top"><h4>Default</h4></th>

				<th align="left" valign="top"><h4>Evaluated</h4></th>

				<th align="left" valign="top"><h4>Type</h4></th>

				<th align="left" valign="top"><h4>Description</h4></th>

			</tr>

				<tr>

					<td align="left" valign="top">accesskey</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html accesskey attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">addLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the label used for the add button</td>

				</tr>

				<tr>

					<td align="left" valign="top">allowRemoveAll</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Determine whether the remove all button will display</td>

				</tr>

				<tr>

					<td align="left" valign="top">allowUpDown</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Determine whether items in the list can be reordered</td>

				</tr>

				<tr>

					<td align="left" valign="top">buttonCssClass</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the css class used for rendering buttons</td>

				</tr>

				<tr>

					<td align="left" valign="top">buttonCssStyle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the css style used for rendering buttons</td>

				</tr>

				<tr>

					<td align="left" valign="top">class</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css class to use for element - it's an alias of cssClass attribute.</td>

				</tr>

				<tr>

					<td align="left" valign="top">cssClass</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css class to use for element</td>

				</tr>

				<tr>

					<td align="left" valign="top">cssErrorClass</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css error class to use for element</td>

				</tr>

				<tr>

					<td align="left" valign="top">cssErrorStyle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css error style definitions for element to use</td>

				</tr>

				<tr>

					<td align="left" valign="top">cssStyle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css style definitions for element to use</td>

				</tr>

				<tr>

					<td align="left" valign="top">disabled</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html disabled attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">downLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the label used for the down button</td>

				</tr>

				<tr>

					<td align="left" valign="top">errorPosition</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Define error position of form element (top|bottom)</td>

				</tr>

				<tr>

					<td align="left" valign="top">headerKey</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the header key of the select box</td>

				</tr>

				<tr>

					<td align="left" valign="top">headerValue</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the header value of the select box</td>

				</tr>

				<tr>

					<td align="left" valign="top">id</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">HTML id attribute</td>

				</tr>

				<tr>

					<td align="left" valign="top">javascriptTooltip</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">Boolean</td>

					<td align="left" valign="top">Use JavaScript to generate tooltips</td>

				</tr>

				<tr>

					<td align="left" valign="top">key</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the key (name, value, label) for this particular component</td>

				</tr>

				<tr>

					<td align="left" valign="top">label</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Label expression used for rendering an element specific label</td>

				</tr>

				<tr>

					<td align="left" valign="top">labelSeparator</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">:</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">String that will be appended to the label</td>

				</tr>

				<tr>

					<td align="left" valign="top">labelposition</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Define label position of form element (top/left)</td>

				</tr>

				<tr>

					<td align="left" valign="top">leftTitle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the left hand title</td>

				</tr>

				<tr>

					<td align="left" valign="top">list</td>

					<td align="left" valign="top"><strong>true</strong></td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Iterable source to populate from. If the list is a Map (key, value), the Map key will become the option 'value' parameter and the Map value will become the option body.</td>

				</tr>

				<tr>

					<td align="left" valign="top">listCssClass</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get css class from</td>

				</tr>

				<tr>

					<td align="left" valign="top">listCssStyle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get css style from</td>

				</tr>

				<tr>

					<td align="left" valign="top">listKey</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get field value from</td>

				</tr>

				<tr>

					<td align="left" valign="top">listLabelKey</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to be used to lookup for localised version of field label</td>

				</tr>

				<tr>

					<td align="left" valign="top">listTitle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get title from</td>

				</tr>

				<tr>

					<td align="left" valign="top">listValue</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get field content from</td>

				</tr>

				<tr>

					<td align="left" valign="top">listValueKey</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Property of list objects to get field value label from</td>

				</tr>

				<tr>

					<td align="left" valign="top">multiple</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Determine whether or not multiple entries are shown</td>

				</tr>

				<tr>

					<td align="left" valign="top">name</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The name to set for element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onblur</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top"> Set the html onblur attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onchange</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onchange attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onclick</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onclick attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">ondblclick</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html ondblclick attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onfocus</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onfocus attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onkeydown</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onkeydown attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onkeypress</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onkeypress attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onkeyup</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onkeyup attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onmousedown</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onmousedown attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onmousemove</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onmousemove attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onmouseout</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onmouseout attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onmouseover</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onmouseover attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onmouseup</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onmouseup attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">onselect</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html onselect attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">removeAllLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the label used for the remove all button</td>

				</tr>

				<tr>

					<td align="left" valign="top">removeLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the label used for the remove button</td>

				</tr>

				<tr>

					<td align="left" valign="top">requiredLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">Boolean</td>

					<td align="left" valign="top">If set to true, the rendered element will indicate that input is required</td>

				</tr>

				<tr>

					<td align="left" valign="top">requiredPosition</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Define required position of required form element (left|right)</td>

				</tr>

				<tr>

					<td align="left" valign="top">rightTitle</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the right hand title</td>

				</tr>

				<tr>

					<td align="left" valign="top">size</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the size of the select box</td>

				</tr>

				<tr>

					<td align="left" valign="top">style</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The css style definitions for element to use - it's an alias of cssStyle attribute.</td>

				</tr>

				<tr>

					<td align="left" valign="top">tabindex</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html tabindex attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">template</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The template (other than default) to use for rendering the element</td>

				</tr>

				<tr>

					<td align="left" valign="top">templateDir</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The template directory.</td>

				</tr>

				<tr>

					<td align="left" valign="top">theme</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">The theme (other than default) to use for rendering the element</td>

				</tr>

				<tr>

					<td align="left" valign="top">title</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the html title attribute on rendered html element</td>

				</tr>

				<tr>

					<td align="left" valign="top">tooltip</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Set the tooltip of this particular component</td>

				</tr>

				<tr>

					<td align="left" valign="top">tooltipConfig</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Deprecated. Use individual tooltip configuration attributes instead.</td>

				</tr>

				<tr>

					<td align="left" valign="top">tooltipCssClass</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">StrutsTTClassic</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">CSS class applied to JavaScrip tooltips</td>

				</tr>

				<tr>

					<td align="left" valign="top">tooltipDelay</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">Classic</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Delay in milliseconds, before showing JavaScript tooltips </td>

				</tr>

				<tr>

					<td align="left" valign="top">tooltipIconPath</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Icon path used for image that will have the tooltip</td>

				</tr>

				<tr>

					<td align="left" valign="top">upLabel</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">the label used for the up button</td>

				</tr>

				<tr>

					<td align="left" valign="top">value</td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top"></td>

					<td align="left" valign="top">false</td>

					<td align="left" valign="top">String</td>

					<td align="left" valign="top">Preset the value of input element.</td>

				</tr>

		</table>

</p>
{% comment %}end snippet id=tagattributes|javadoc=false|url=struts2-tags/inputtransferselect.html {% endcomment %}

__Example__



{% comment %}start snippet id=example|lang=xml|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}

```xml

 <-- minimum configuration -->
 <s:inputtransferselect
      label="Favourite Cartoons Characters"
      name="cartoons"
      list="{'Popeye', 'He-Man', 'Spiderman'}"
  />


```

{% comment %}end snippet id=example|lang=xml|javadoc=true|url=org.apache.struts2.components.InputTransferSelect {% endcomment %}