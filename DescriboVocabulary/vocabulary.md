
# TK Labels : version 1.0


### Keywords
TK Labels<br />

### Classes
[Action](#Action) [ConsumeAction](#ConsumeAction) [CreateAction](#CreateAction) [CreativeWork](#CreativeWork) [Dataset](#Dataset) [Entity](#Entity) [Event](#Event) [File](#File) [Organization](#Organization) [Person](#Person) [Place](#Place) [TKLabel](#TKLabel) [Thing](#Thing) [UpdateAction](#UpdateAction)

### Description
The Traditional Knowledge (TK) Labels are an initiative for Indigenous communities and local organizations.
This Vocabulary is used to create a TKLabels dataset with Describo.<br />


---
## <a name="Action"></a> Action (https://schema.org/Action) <br />
SubclassOf: [Thing](#Thing)<br />

An action performed by a direct agent and indirect participants upon a direct object.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **agent** | https://schema.org/agent | The direct performer or driver of the action (animate or inanimate). E.g. John wrote a book. | Person, Organisation | false | true |
| **object** | https://schema.org/object | The object upon which the action is carried out, whose state is kept intact or changed. Also known as the semantic roles patient, affected or undergoer (which change their state) or theme (which doesn't). E.g. John read a book. | ANY | false | true |
| **participant** | https://schema.org/participant | Other co-agents that participated in the action indirectly. E.g. John wrote a book with Steve. | Person, Organization | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="ConsumeAction"></a> ConsumeAction (https://schema.org/ConsumeAction) <br />
SubclassOf: [Action](#Action)<br />

The act of ingesting information/resources/food.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **agent** | https://schema.org/agent | The direct performer or driver of the action (animate or inanimate). E.g. John wrote a book. | Person, Organisation | false | true |
| **object** | https://schema.org/object | The object upon which the action is carried out, whose state is kept intact or changed. Also known as the semantic roles patient, affected or undergoer (which change their state) or theme (which doesn't). E.g. John read a book. | ANY | false | true |
| **participant** | https://schema.org/participant | Other co-agents that participated in the action indirectly. E.g. John wrote a book with Steve. | Person, Organization | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="CreateAction"></a> CreateAction (https://schema.org/CreateAction) <br />
SubclassOf: [Action](#Action)<br />

The act of deliberately creating/producing/generating/building a result out of the agent.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **agent** | https://schema.org/agent | The direct performer or driver of the action (animate or inanimate). E.g. John wrote a book. | Person, Organisation | false | true |
| **object** | https://schema.org/object | The object upon which the action is carried out, whose state is kept intact or changed. Also known as the semantic roles patient, affected or undergoer (which change their state) or theme (which doesn't). E.g. John read a book. | ANY | false | true |
| **participant** | https://schema.org/participant | Other co-agents that participated in the action indirectly. E.g. John wrote a book with Steve. | Person, Organization | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="CreativeWork"></a> CreativeWork (https://schema.org/CreativeWork) <br />
SubclassOf: [Thing](#Thing)<br />

The most generic kind of creative work, including books, movies, photographs, software programs, etc.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **about** | https://schema.org/about | The subject matter of the content. | ANY, URL | false | true |
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **author** | https://schema.org/author | The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably. | Person, Organisation | false | true |
| **contentLocation** | https://schema.org/contentLocation | The location depicted or described in the content. For example, the location in a photograph or painting. | Place | false | true |
| **contributor** | https://schema.org/contributor | A secondary contributor to the CreativeWork or Event. | Person, Organisation | false | true |
| **datePublished** | https://schema.org/datePublished | DateTime, Date of first publication or broadcast. For example the date a CreativeWork was broadcast or a Certification was issued. | Date, DateTime | true | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **hasPart** | https://schema.org/hasPart | Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense). | CreativeWork, URL, File, Dataset, TKLabel | false | true |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **keywords** | https://schema.org/keywords | Keywords or tags used to describe some item. Multiple textual entries in a keywords list are typically delimited by commas, or by repeating the property.  | TEXT, URL | false | true |
| **license** | https://schema.org/license | A license document that applies to this content, typically indicated by URL. | CreativeWork, URL | true | true |
| **mainEntity** | https://schema.org/mainEntity | Indicates the primary entity described in some page or other CreativeWork. | ANY, URL | false | false |
| **mentions** | https://schema.org/mentions | Indicates that the CreativeWork contains a reference to, but is not necessarily about a concept. | ANY | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **publisher** | https://schema.org/publisher | The publisher of the creative work. | Person, Organisation | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Dataset"></a> Dataset (https://schema.org/Dataset) <br />
SubclassOf: [CreativeWork](#CreativeWork)<br />

A body of structured information describing some topic(s) of interest.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **about** | https://schema.org/about | The subject matter of the content. | ANY, URL | false | true |
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **author** | https://schema.org/author | The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably. | Person, Organisation | false | true |
| **contentLocation** | https://schema.org/contentLocation | The location depicted or described in the content. For example, the location in a photograph or painting. | Place | false | true |
| **contributor** | https://schema.org/contributor | A secondary contributor to the CreativeWork or Event. | Person, Organisation | false | true |
| **datePublished** | https://schema.org/datePublished | DateTime, Date of first publication or broadcast. For example the date a CreativeWork was broadcast or a Certification was issued. | Date, DateTime | true | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **hasPart** | https://schema.org/hasPart | Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense). | CreativeWork, URL, File, Dataset, TKLabel | false | true |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **keywords** | https://schema.org/keywords | Keywords or tags used to describe some item. Multiple textual entries in a keywords list are typically delimited by commas, or by repeating the property.  | TEXT, URL | false | true |
| **license** | https://schema.org/license | A license document that applies to this content, typically indicated by URL. | CreativeWork, URL | true | true |
| **mainEntity** | https://schema.org/mainEntity | Indicates the primary entity described in some page or other CreativeWork. | ANY, URL | false | false |
| **mentions** | https://schema.org/mentions | Indicates that the CreativeWork contains a reference to, but is not necessarily about a concept. | ANY | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **publisher** | https://schema.org/publisher | The publisher of the creative work. | Person, Organisation | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Entity"></a> Entity (_:Entity) <br />
SubclassOf: [Thing](#Thing)<br />

The most generic type of entity.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **endDate** | https://schema.org/endDate | The end date and time of the item. | Date, DateTime, Text | false | false |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
| **startDate** | https://schema.org/startDate | The start date and time of the item. | Date, DateTime, Text | false | false |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Event"></a> Event (https://schema.org/Event) <br />
SubclassOf: [Entity](#Entity)<br />

An event happening at a certain time and location, such as a concert, lecture, or festival.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **endDate** | https://schema.org/endDate | The end date and time of the item. | Date, DateTime, Text | false | false |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
| **startDate** | https://schema.org/startDate | The start date and time of the item. | Date, DateTime, Text | false | false |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="File"></a> File (https://schema.org/MediaObject) <br />
SubclassOf: [CreativeWork](#CreativeWork)<br />

A file object, such as an image, video, audio, or text object embedded in a web page or a downloadable dataset<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **about** | https://schema.org/about | The subject matter of the content. | ANY, URL | false | true |
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **author** | https://schema.org/author | The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably. | Person, Organisation | false | true |
| **contentLocation** | https://schema.org/contentLocation | The location depicted or described in the content. For example, the location in a photograph or painting. | Place | false | true |
| **contributor** | https://schema.org/contributor | A secondary contributor to the CreativeWork or Event. | Person, Organisation | false | true |
| **datePublished** | https://schema.org/datePublished | DateTime, Date of first publication or broadcast. For example the date a CreativeWork was broadcast or a Certification was issued. | Date, DateTime | true | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **hasPart** | https://schema.org/hasPart | Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense). | CreativeWork, URL, File, Dataset, TKLabel | false | true |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **keywords** | https://schema.org/keywords | Keywords or tags used to describe some item. Multiple textual entries in a keywords list are typically delimited by commas, or by repeating the property.  | TEXT, URL | false | true |
| **license** | https://schema.org/license | A license document that applies to this content, typically indicated by URL. | CreativeWork, URL | true | true |
| **mainEntity** | https://schema.org/mainEntity | Indicates the primary entity described in some page or other CreativeWork. | ANY, URL | false | false |
| **mentions** | https://schema.org/mentions | Indicates that the CreativeWork contains a reference to, but is not necessarily about a concept. | ANY | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **publisher** | https://schema.org/publisher | The publisher of the creative work. | Person, Organisation | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Organization"></a> Organization (https://schema.org/Organization) <br />
SubclassOf: [Thing](#Thing)<br />

An organization such as a school, NGO, corporation, club, etc.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **address** | https://schema.org/address | Physical address of the item. | TextArea | false | true |
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **dissolutionDate** | https://schema.org/dissolutionDate | The date that this organization was dissolved.  | Date | false | false |
| **foundingDate** | https://schema.org/foundingDate | The date that this organization was founded. | Date | false | false |
| **foundingLocation** | https://schema.org/foundingDateLocation | The place where this organization was founded. | Place | false | false |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Person"></a> Person (https://schema.org/Person) <br />
SubclassOf: [Thing](#Thing)<br />

A person (alive, dead, undead, or fictional).<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **additionalName** | https://schema.org/additionalName | An additional name for a Person, can be used for a middle name. | Text | false | false |
| **birthDate** | https://schema.org/birthDate | Date of birth. | Date, DateTime | false | false |
| **deathDate** | https://schema.org/deathDate | Date of death. | Date, DateTime | false | false |
| **familyName** | https://schema.org/familyName | Family name. In the U.S., the last name of a Person. | Text | false | false |
| **givenName** | https://schema.org/givenName | Given name. In the U.S., the first name of a Person. | Text | false | false |
| **homeLocation** | https://schema.org/homeLocation | A contact location for a person's residence. | Place | false | false |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Place"></a> Place (https://schema.org/Place) <br />
SubclassOf: [Thing](#Thing)<br />

Entities that have a somewhat fixed, physical extension.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **address** | https://schema.org/address | Physical address of the item. | TextArea | false | true |
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **geo** | https://schema.org/geo | The geo coordinates of the place. | GeoCoordinates, GeoShape | false | true |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="TKLabel"></a> TKLabel (#TKLabel) <br />
SubclassOf: [Thing](#Thing)<br />

A TK Label<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|

<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="Thing"></a> Thing (https://schema.org/Thing) <br />
SubclassOf: <br />

The most generic type of item.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **alternateName** | https://schema.org/alternateName | An alias for the item. | Text | false | true |
| **description** | https://schema.org/description | A description of the item. | TextArea | false | true |
| **identifier** | https://schema.org/identifier | The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links.  | Text, URL | false | true |
| **potentialAction** | https://schema.org/potentialAction | Indicates a potential Action, which describes an idealized action in which this thing would play an 'object' role. | CreateAction, ConsumeAction, UpdateAction | false | true |
| **sameAs** | https://schema.org/sameAs | URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website. | URL | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>


---
## <a name="UpdateAction"></a> UpdateAction (https://schema.org/UpdateAction) <br />
SubclassOf: [Action](#Action)<br />

The act of managing by changing/editing the state of the object.<br />

| Property              |  ID | Description | Expected Data  |  Is Required | Multiple Values  |
|:----------------------|:----|:-------------|:---------------|:-------------|:-----------------|
| **agent** | https://schema.org/agent | The direct performer or driver of the action (animate or inanimate). E.g. John wrote a book. | Person, Organisation | false | true |
| **object** | https://schema.org/object | The object upon which the action is carried out, whose state is kept intact or changed. Also known as the semantic roles patient, affected or undergoer (which change their state) or theme (which doesn't). E.g. John read a book. | ANY | false | true |
| **participant** | https://schema.org/participant | Other co-agents that participated in the action indirectly. E.g. John wrote a book with Steve. | Person, Organization | false | true |
<br/><br/>
<style>
body {
  font-family: Arial, sans-serif;
  color: #333;
  font-color: #334155;
}
h1 {
  color: #1e40af;
}

h2 {
  color: #047857
}
h3 {
  color: #2563eb
}
a {
  color: #047857;
}
h2 a {
  color: #0284c7;
  font-size: 1rem;
}
table {
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.9em;
    font-family: sans-serif;
    min-width: 400px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
table thead tr {
    background-color: #22d3ee;
    color: #334155;
    text-align: left;
}
table th,
table td {
    padding: 12px 15px;
}
table tbody tr {
    border-bottom: 1px solid #dddddd;
}
table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
table tbody tr:last-of-type {
    border-bottom: 2px solid #009879;
}
table tbody tr.active-row {
    font-weight: bold;
    color: #009879;
}
</style>

