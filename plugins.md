---
layout: page_toc
permalink: plugins.html
title: Plugins
---

Specify works with the GEOLocate and Google Earth web services to assist with georeferencing and visualising specimen records. GEOLocate and Google Earth can be accessed via the **Locality** form for individual records, or via the **Plugins** module for record sets.

## GEOLocate

GEOLocate uses the **Locality** description and geography to find latitude and longitude coordinate data for specimen records.

### Using GEOLocate in the Locality form

To georeference a specimen record in the **Locality** form:

1.  Complete the **Geography** and **Locality** fields:

> &lt;&lt;image&gt;&gt;
>
> Note that the **Geography** field must contain at least a country name; GEOLocate will not work if only a continent name is entered.

1.  Save the **Locality** form then re-open it by clicking on the Edit symbol &lt;&lt;image&gt;&gt;

2.  Click the **GEOLocate** button at the bottom of the **Locality** form:

> &lt;&lt;image&gt;&gt;
>
> A dialogue window will indicate whether or not GEOLocate has returned results:

&lt;&lt;image&gt;&gt;

1.  If there are no results, click **OK** to return to the **Locality** form. If there are results, click **Yes** to view them in the **GEOLocate results window** (p. 202).

### Using GEOLocate in the Plugins module

GEOLocate can be used to quickly georeference batches of records. To launch GEOLocate from the **Plugins** module:

1.  Open the **Plugins** module by clicking on the **Plugins** button in the task bar

2.  Click and drag a record set on to the **GEOLocate** icon in the side bar:

> &lt;&lt;image&gt;&gt;

If the record set contains records that do not have **Geography** information and/or records that already have latitude and longitude, a warning will be issued:

&lt;&lt;image&gt;&gt;

> Click **Continue** if you want to continue the georeferencing process regardless, or **Cancel** if you want to change the record set first. Do not click **Continue** unless you want to overwrite the existing latitude and longitude values, which is probably *not* what you want to do.
>
> The GEOLocate progress window will indicate how many of the records in the record set have been georeferenced:
>
> &lt;&lt;image&gt;&gt;
>
> A dialogue window will indicate whether or not GEOLocate has found any matching localities.

1.  If there are no results click **OK** to return to the **Plugins** screen. If there are matching records, click **Yes** to view them in the **GEOLocate results window** (below).

### GEOLocate results window

&lt;&lt;image&gt;&gt;

-   If there is more than one result, you can scroll through the list of results to view their locations on the map. The first result in the list is not always the correct one: in the example above, the first result is on Sumatra, not Sulawesi.

-   You can zoom in and out to get a more detailed view or a better overview by clicking the + and – buttons, moving the pointer in the zoom scale, or scrolling your mouse wheel. It can be useful to zoom out until you see the place marks for all the results so you can compare them easily. You can also pan the map by holding the left-hand mouse button down and dragging the map into the desired position. The result that is highlighted in the list (the first result in the above example) will have a green place marker; the other results will have red place markers:

    &lt;&lt;image&gt;&gt;

<!-- -->

-   You can adjust the georeference by clicking on the place marker of the highlighted record (i.e. whichever one is green), holding the left mouse button down and dragging the marker to the desired position:

    &lt;&lt;image&gt;&gt;

-   The new latitude and longitude of the green dot will appear under **Position** in the **Correction (Green) Marker Properties** box (there is no need to click the **Apply** button):

> &lt;&lt;image&gt;&gt;
>
> (The latitude and longitude displayed under the map are the mouse position, not the position of the green marker.)

-   You can make the green marker jump back to its original position by clicking on the original red marker. The other fields in the **Correction (Green) Marker Properties** box have not been implemented in Specify, so any data entered in there won’t be stored in the database.

-   To save the geocode, click the **Accept** button at the bottom of the form. When using GEOLocate from the **Locality** form, the GEOLocate window will be closed; when using GEOLocate in the **Plugins** tab, the GEOLocate results window will display the results for the next record in the record set.

  --------------------------------------------------------------------------------------------------------------------
  #### **Caution!**

  If GEOLocate results are accepted, they will overwrite any existing data in the **Latitude and longitude** fields.
  --------------------------------------------------------------------------------------------------------------------
  --------------------------------------------------------------------------------------------------------------------

#### Other controls

-   Clicking the **GEOLocate Web** button will transfer the result of the GEOLocate query to the GEOLocate website. The GEOLocate website will display exactly the same information as the plugin in Specify, but uses Google Maps as the base map, which might give more map detail. Changes you make on the GEOLocate website will not be stored in the database, so it is a safe option if you need to play around a bit to determine the correct geocode.

-   Clicking the **Help** button will open **Specify Help**

-   When GEOLocate is used in the **Locality** form, clicking **Skip** will close the GEOLocate window; when GEOLocate is used in the **Plugins** tab, clicking **Skip** will get you to the results of the next record in the record set

-   Clicking the **Quit** button closes the GEOLocate window.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### **Note**

  When you georeferenced a specimen using GEOLocate, it will populate **Latitude and longitude, Datum**, **Source** and **Protocol**. **Uncertainty** still has to be entered in the **Locality** form.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## World Wind

World Wind is an open-source, 3D, interactive world viewer. It can be used in Specify to display the locality of **Collection object** records, or to map localities during data entry.

Clicking the **Display in World Wind** button will open the NASA World Wind application. A text box at the top of the World Wind window allows latitude and longitude or a locality name to be entered:

&lt;&lt;image&gt;&gt;

Press **Enter** after typing the locality name. The location is then displayed on a World Wind map:

&lt;&lt;image&gt;&gt;

If the **Collection object** has been georeferenced, or if there is a locality in the **Locality** form, World Wind will automatically plot the location on the map once the button is clicked. **Never close the window by clicking the** OK **button unless you want to change the geocode in the** Locality **record. **

The following mouse and keyboard controls operate in World Wind:

For a mouse with a scroll wheel:

----------------------------------------------------------------------------------------------------------------------------------
  **Pan **             Click and drag the left mouse button to pan in all directions
-------------------- -------------------------------------------------------------------------------------------------------------
  **Zoom **            Use the scroll wheel on the mouse or click and drag the left and right mouse buttons to zoom in and out

  **Tilt **            Click and drag the right mouse button up and down, or press the **PgUp** and **PgDn** keys to tilt the map.

  **Rotate **          Click and drag the right mouse button left and right to rotate the map.
​                       
                       *Note:* crossing the top and bottom half of the screen while rotating will change the rotation direction.

  **Stop **            Press the spacebar to stop the map

  **Reset heading **   Press **N** to reset the heading

  **Reset all **       Press **R** to reset all settings
  ----------------------------------------------------------------------------------------------------------------------------------

For a mouse with a single button:

  **Pan **             Click and drag the left mouse button to pan in all directions. Click the left mouse button once to center the view.
-------------------- -----------------------------------------------------------------------------------------------------------------------------
  **Zoom **            Press and hold the **Ctrl** key on the keyboard and click and drag the left mouse button up and down to zoom in and out
  **Tilt **            Press and hold the **Shift** key on the keyboard and click and drag the left mouse button up and down to tilt the map
  **Rotate **          Press and hold the **Shift** key on the keyboard and click and drag the left mouse button to rotate the map left and right.
  **Stop **            Press the spacebar to stop the map
  **Reset heading **   Press **N** to reset the heading
  **Reset all **       Press **R** to reset all settings

## Google Earth

The Google Earth plugin is used as a means of visualising **Collection object** records from Specify in Google Earth. The full version of Google Earth 4.3 (or higher) must be installed on the local computer for the Specify Google Earth plugin to work.

Specify plots **Collection object** records in Google Earth based on the latitude and longitude provided in the **Locality** form. Google Earth can either be launched in the **Locality** form, or by dragging and dropping a record set onto the Google Earth icon in the **Plugins** module.

Before plotting specimen records using **Google Earth**, make sure that all records in the record set contain latitude and longitude values.

### Using Google Earth in the Locality form

To launch Google Earth from the **Locality** form:

1.  Open a **Collection object** record and click on the **Locality** information symbol to view the **Locality** form:

> &lt;&lt;image&gt;&gt;

1.  Click the **Display in Google Earth** button at the bottom of the **Locality** form:

> &lt;&lt;image&gt;&gt;

-   Google Earth will open, and the **Collection object** records in the record set will be mapped:

> &lt;&lt;image&gt;&gt;

### Using Google Earth in the Plugins module

To launch Google Earth from the **Plugins** module:

1.  Open the **Plugins** module by clicking on the **Plugins** button in the task bar

2.  Click and drag a Record set on to the **Google Earth** icon in the side bar:

> &lt;&lt;image&gt;&gt;

-   Google Earth will open, and the **Collection object** records in the record set will be mapped:

> &lt;&lt;image&gt;&gt;

-   Collection object information is shown in the Google Earth information window:

> &lt;&lt;image&gt;&gt;

# Appendices

## 1. Abbreviations

  **Term**         **Abbreviation**
---------------- ------------------
  approximately    approx.
  avenue           ave
  boulevard        bvd
  circa            ca. *or* c.
  circuit          cct
  close            cl.
  court            ct
  crescent         cres.
  degrees          deg. *or* °
  drive            dr.
  east             E
  esplanade        esp.
  feet             ft *or* '
  freeway          fwy
  heights          hts
  highway          hwy
  inch             in. *or* ''
  Island/Islands   I./Is
  junction         jnc.
  kilometres       km
  metres           m
  mile             mi.
  minutes          min. *or* ′
  more or less     +/-
  Mount            Mt
  National Park    NP
  north            N
  parade           pde
  place            pl.
  point            pt
  reserve          res.
  road             rd
  seconds          sec., s *or* ″
  south            S
  street           st
  terrace          tce
  track            trk
  west             W
  yard             yd

Note that Road, Street, Track etc. should only be abbreviated for named places, and not for general use, e.g.:

-   5 km along the Daylesford–Malmsbury **Rd** …

> BUT

-   5 km along the **road** to Daylesford from Malmsbury …

## 2. Examples of determination records

The following examples demonstrate how a range of determinations should be entered into MELISR. Because the **Current** check box is automatically ticked when you add a new determination, it is easier to enter the determinations in chronological order.

######## MEL 2088758

This sheet has one old label bearing a name and author combination that appears to be an error, plus one MEL annotation from the Foreign Fabaceae Project.

&lt;&lt;image&gt;&gt;

1.  The author of *Pongamia glabra* is Vent.; *Pongamia glabra* Lamarck is not listed in Tropicos, and it is not clear whether it is a homonym, an isonym or an error. Because we know that *Pongamia glabra* Vent. is a synonym of the name to which the specimen is currently determined, *Millettia pinnata*, it’s fairly safe to assume that ‘Lamark’ is just an error. *Pongamia glabra* Vent. can be entered as the **Taxon name**, and *Pongamia glabra* Lamark should be entered in **Det. notes** to record what is actually written on the label:

> &lt;&lt;image&gt;&gt;

1.  Existing annotations for special projects, such as the Foreign Fabaceae Project, should be entered with ‘Annot.’ in the **Det. type** field and the project name as the determiner, but note that ‘Annot.’ and project names should not be used for new determinations – please always use Det. or Conf. for new determinations:

> &lt;&lt;image&gt;&gt;

######## MEL 2068911

This specimen has three labels that bear names: the original collecting label bearing a taxon name written in F.M. Bailey’s hand; an old MEL label with the same name in Mueller’s handwriting; and a more recent determination on a MEL det. slip that includes extra information about the taxon concept. Even though Bailey and Mueller have given the same name to the specimen, their determinations may be of historical interest and should both be recorded.

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

1.  Enter ‘Bailey, F.M.’ as the determiner, and tick the **Determiner inferred** box to indicate that the determiner was inferred from the label:

> &lt;&lt;image&gt;&gt;
>
> Note that, if you didn’t recognise the handwriting on the original collecting label, and the taxon name is the same as one of the later determinations, there’s no need to enter it as a separate determination.

1.  Mueller’s determination can be entered in the same way as Bailey’s determination:

> &lt;&lt;image&gt;&gt;

1.  For Helen Aston’s determination (which is partly obscured in the image above), ‘eastern variant’ should be entered in the **Extra information** field:

> &lt;&lt;image&gt;&gt;

######## MEL 2040511

This specimen has an older, typed label that appears to have been taken from a list of exsiccata specimens, plus a name change written directly on the moss packet.

&lt;&lt;image&gt;&gt;

1.  ‘*Dicranum aciculare*’ on the typed label can be treated as the first determination. The author on the label (H. R.) differs from the author given in Tropicos (Hedw.), and a synonym is also given. *Dicranum aciculare* Hedw. should be selected from the **Taxon name** list, and both names and authors on the original label should be entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The current determination has not been attributed to a person or a project, so only the **Taxon name** field (and the **Current** box) need to be filled in:

> &lt;&lt;image&gt;&gt;

######## MEL 299373

This specimen bears two names: *Crotolaria* *pterocaule*, which was not in the **Taxon** table, and a recent MEL annotation from the Foreign Fabaceae Project.

&lt;&lt;image&gt;&gt;

1.  *Crotolaraia pterocaule* is a validly published name, so it can be added to the **Taxon** table, and the determination can be entered without a **Determiner**.

> &lt;&lt;image&gt;&gt;
>
> If you are familiar with the handwriting, you could choose to enter the determiner’s name and tick the **Determiner inferred** box.

1.  The current annotation is straightforward:

> &lt;&lt;image&gt;&gt;

######## MEL 590554

This specimen has three labels: an old MEL label with a taxon name in Mueller’s handwriting; an annotation slip with the same name as the blue MEL label, and an uncertain redetermination.

&lt;&lt;image&gt;&gt;

1.  Enter ‘Mueller, F.’ as the determiner, and tick the **Determiner inferred** box to indicate that the determiner was inferred from the label:

> &lt;&lt;image&gt;&gt;

1.  ‘Capparidaceae, revised by M. Jacobs’ should be entered in the **Det. notes** field, as it provides useful information about the determiner’s knowledge of the family:

> &lt;&lt;image&gt;&gt;

1.  Hewson’s determination has a qualifier before the taxon name. By default, the **Qualifier rank** will be set to the lowest rank to which the specimen has been determined. Because the qualifier on this det. slip appears before the genus, not the species epithet, you need to select ‘genus’ from the **Qualifier rank** pick list. ‘Flora of Australia’ should be selected from the **Flora** pick list:

> &lt;&lt;image&gt;&gt;

######## MEL 2347722

This specimen has one label in the collector’s handwriting that bears two synonyms, and a recent MEL determination slip.

&lt;&lt;image&gt;&gt;

1.  If there is more than one name on a single label, and they are written in the same handwriting, they can be treated as a single determination. In this case, it is not clear whether the name being applied to the specimen is *Lespedeza daurica* or *Trifolium dauricum*. Unless there is reason to think otherwise, assume that the first (and in this case, more prominent) name is the name the specimen is being determined to. On this label, there are two spellings of the species epithet *davurica*, both of which are incorrect. The correct spelling should be selected from the **Taxon name** drop-down list. Enter all the names in the **Det. notes** field to record exactly what appears on the label:

> &lt;&lt;image&gt;&gt;
>
> If you were familiar with the collector’s handwriting, and knew that the label was written by O.W. Borrell, you could choose to enter him as the determiner and tick the **Determiner** i**nferred** box.

1.  The current determination is straightforward:

> &lt;&lt;image&gt;&gt;

######## MEL 248757

There are three taxon names on this sheet: one written directly on the sheet in Steetz’s hand; a small, typed label reading ‘*Psoralea plicata* Del. Aeg. Sup.’; and a more recent determination on a MEL det. slip.

&lt;&lt;image&gt;&gt;

1.  A taxon name written on the sheet in Steetz’s hand can be treated as a determination. ‘Steetz, J.’ should be entered as the determiner, and the **Determiner inferred** box ticked:

> &lt;&lt;image&gt;&gt;

1.  The current determination is straightforward. Note that, if known, the determiner’s full initials should be entered in the **Determiner** field, even if only one initial is given on the det. slip:

> &lt;&lt;image&gt;&gt;
>
> The ‘*Psoralea plicata* Del. Aeg. Sup.’ label relates to one of Steetz’s collections and should not be treated as a determination. ‘Aeg. Sup.’ can be entered in the **Original collection** field:
>
> &lt;&lt;image&gt;&gt;

######## MEL 2347754

This specimen has three labels with taxon names. Although the first taxon name on the bottom two labels is the same, they should be entered as separate determinations because they contain different nomenclatural information.

&lt;&lt;image&gt;&gt;

1.  Because we treat the first name on a label as the name the specimen was determined to (unless there is reason to interpret the label differently), this determination would have *Lespedesza polystachya* in the **Taxon name** field, and both names on the label entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The second label would be entered in the same way (i.e. with the correct spelling of *L. polystachya* in the **Taxon name** field, and the full list of names in **Det. notes**):

> &lt;&lt;image&gt;&gt;

1.  The current determination would be entered as follows:

> &lt;&lt;image&gt;&gt;

######## MEL 2277834

This specimen has four separate determinations. The large, yellowish label at the bottom of the label looks like a herbarium label of sorts, so the names on that label wouldn’t be considered determinations. The oldest determination is on the label in Mueller’s hand, directly above which is a redetermination in someone else’s handwriting. To the right of the specimen is a redetermination by Bentham, and the most recent annotation is a MEL det. slip that indicates the type status of the specimen.

&lt;&lt;image&gt;&gt;

1.  Mueller’s determination should be entered with ‘Mueller, F.’ as the determiner, and the **Determiner inferred** box ticked. Mueller has written ‘*Grevillea dallachiana* Ferd. Mueller \[…\] *parviflora*’ on the label. No infraspecific taxa of *G. dallachiana* have been published, and Mueller listed *G. dallachiana* and *G. parviflora* as distinct taxa in an 1853 report. The best option in this situation is to enter *Grevillea dallachiana* in the **Taxon name** field and enter the names as they appear on the label in the **Det. notes** field:

> &lt;&lt;image&gt;&gt;

1.  ‘G. alpestris Meisn.’ is written directly above the first determination. This should be entered as a separate determination, with only the **Taxon name** field filled in:

> &lt;&lt;image&gt;&gt;

1.  The determination bearing the name *G. alpina* indicates that Bentham provided the name, so he can be entered as the determiner. The note below the name should be entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The most recent det. slip is an AVH annotation that repeats the current name and provides the type status. There is no need to include the current name from the AVH annotation as a separate determination, as it doesn’t add any information; it is better to keep Bentham’s determination as the current one, because it is more informative. The type determination needs to be added with the **Det. type** as ‘Type status’ rather than ‘AVH annot.’, and the **Type status** and **Type qualifier** fields filled in. Where the specimen is stored under the typified name, tick the **Stored under this name** field (type specimens are stored under the most recently published name of which the specimen is a type). Make sure that the **Current** box is not ticked for ‘Type status’ determinations:

> &lt;&lt;image&gt;&gt;

######## MEL 524439

There are three labels with names on this specimen. The middle label is very difficult to read, so there’s no need to add it as a determination. The top label is written in A.C. Beauglehole’s hand, and bears the same taxon name as the det. slip at the bottom of the sheet. Whether or not these should be treated as separate determinations is quite subjective. If you consider Beauglehole to be the determiner of the name on the top handwritten label then they should be entered as separate determinations, otherwise a single determination record would suffice.

&lt;&lt;image&gt;&gt;

1.  If you are interpreting the taxon name written on the top label by Beauglehole as a determination, enter it with ‘Beauglehole, A.C.’ as the determiner and tick the **Determiner inferred** box:

> &lt;&lt;image&gt;&gt;

1.  The La Trobe University Herbarium det. slip is straightforward:

> &lt;&lt;image&gt;&gt;