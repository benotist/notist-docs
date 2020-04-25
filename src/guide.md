---
layout: docs
title: Using Notist
---


<div id="doc-header" class="doc-header text-center">
    <h1 class="doc-title"><i class="icon fa fa-paper-plane"></i> {{ title }}</h1>
</div>
<div class="doc-body row">
    <div class="doc-content col-md-9 col-12 order-1">
        <div class="content-inner">
            <section id="presentations" class="doc-section">
                <h2 class="section-title">Managing presentations</h2>
                <div class="section-block">
                    <h3 class="block-title" id="add-presentation">Adding a new presentation</h3>
                    <p>
                    Click the + icon to start adding a new presentation. If this is a completely
                    new talk then select "New presentation", if you would like to start by copying
                    details from a previous talk then select Variation on an existing presentation".
                    </p>
                    <p>
                    If you are creating a Variation of an existing presentation we will then ask
                    you to choose which presentation, and also which of the assets related to that
                    presentation you would like to copy.
                    </p>
                    <p>At this point you can upload your slides if you have them.</p>
                    <p>
                    The next step is to assign this presentation to an event. So that we can see
                    if the event already exists on Notist we ask for the location and date and time
                    of the event, if we find matches we will show them to you so you can select one
                    if it is your event. If we find no matches, or this is another event to the ones
                    we show you, you can go on to add details of the event. See editing events for
                    more details.
                    </p>
                    <p>
                    You can now add the basic details of your presentation, saving these details
                    will save your presentation as a draft.
                    </p>
                    <h3 class="block-title" id="add-slidedeck">Adding a slide deck</h3>
                    <p>You can upload your presentation</p>
                    <p>
                    You have two options when adding a slidedeck to your presentation. If you have
                    a PDF file of your slides, then you can upload this directly to Notist. If your
                    slides are hosted elsewhere - for example of Slides.com - you can give us a link
                    and we will embed them on the presentation page.
                    </p>
                    <h4>Uploading a PDF</h4>
                    <p>
                    Export a PDF file from your presentation software and upload this file. If you
                    have presenter notes in your original deck and would like us to import those
                    as a description for your slide, add a second deck which is an export with notes
                    included.
                    </p>
                    <h4>Processing Your Slides</h4>
                    <p>
                    We will upload your slide deck(s) and try to extract any text from the slides
                    themselves and your speaker notes.
                    </p>
                    <p>
                    Slides will be saved as images using the most appropriate format for the type
                    of content on the slide. We aim to keep your text crisp and images clear.
                    </p>
                    <p>
                    This can take a little while, but you can leave the page and come back later.
                    </p>
                    <h4>After Uploading</h4>
                    <p>
                    You can now view and edit the deck, and make any changes to individual slides.
                    </p>
                    <h3 class="block-title" id="two-pdfs">Why two PDFs?</h3>
                    <p>
                    When you upload a slide deck to Notist, there's the option to add two different
                    PDFs. What's that all about?
                    </p>
                    <p>In summary:</p>
                    <ol>
                    <li>
                        Always upload the Slidedeck PDF (first) file. This is used for creating your
                        slides.
                    </li>
                    <li>
                        The presenter notes PDF is optional, and is used for text only&nbsp;<em>in addition</em>
                        to the first PDF
                    </li>
                    </ol>
                    <h4>Slidedeck PDF</h4>
                    <p>
                    The first upload field is for the slide deck PDF. This is your nice, pristine
                    set of slides that we will use to create the images that make up your slide deck
                    when shown on the presentation page.
                    </p>
                    <p>
                    If you're uploading a deck, you always need to add this file. It's the important
                    one, the head honcho, the main deal.
                    </p>
                    <p>
                    We have
                    <a href="#image-quality">some tips for getting the best quality</a>,
                    but if it's a reasonably recent deck (rather than something dusty you've dug
                    out from the early 2000s) you should be able to just export from Powerpoint or
                    Keynote and upload it.
                    </p>
                    <p>
                    We'll then churn through and make it into images, and extract any text we find
                    on the slides and add that to the description field for each slide. This helps
                    in making notes, and can be useful for search indexing and for users who can't
                    read images well but might like the text.
                    </p>
                    <h4>Presenter notes PDF</h4>
                    <p>
                    The second field is for a copy of your presentation that has been exported with
                    the presenter notes turned on. This is entirely optional, and it only works if
                    you upload it alongside the main slide deck PDF. This is great for presenters
                    who make heavy use of notes.
                    </p>
                    <p>
                    You can create the presenter notes PDF by exporting from Powerpoint or Keynote
                    and enabling the "include presenter notes" option. This option then adds the
                    text from your presenter notes to the PDF alongside the image.
                    </p>
                    <p>
                    We then run through this second PDF and extract all that extra text, adding it
                    to the notes field for each slide. No images are used in this PDF - just the
                    text.
                    </p>
                    <p>
                    It's important if you use this option, that your presenter notes PDF has the
                    same number of pages as the main PDF. We match them up by page number, so whatever
                    notes are on Page 12 of the notes PDF get assigned to whatever slide is on Page
                    12 of the main slide deck PDF.
                    </p>
                    <h3 class="block-title" id="image-quality">Getting the best image quality</h3>
                    <p>
                    We always want your slides to look their best on Notist, and we'll be improving
                    our PDF importer to make sure that's always the case. If you upload a slide deck
                    and find it looks a bit low-res, or is rotated strangely, here's a quick fix
                    you can try.
                    </p>
                    <h4>Delete the old deck</h4>
                    <p>
                    You don't want those crummy, fuzzy, low-res images so in the Slidedeck editor,
                    scroll to the bottom and use the red Delete This Deck button to get rid.
                    </p>
                    <h4>Re-save your PDF</h4>
                    <p>
                    PDFs are scalable vector files, so they should look good at any size. They usually
                    come coded with a default size, which is set to match a projector. Most projectors
                    actually use very low resolutions, especially compared to the nice big images
                    we want on Notist.
                    </p>
                    <p>
                    If we use images at that size, they'll look rubbish. We can get around it by
                    re-saving the PDF to target a larger output size.
                    </p>
                    <p>
                    <em>(We're working adding better intelligence to the process to get around this.)</em>
                    </p>
                    <h4>Using Preview on a Mac</h4>
                    <p>
                    Open your PDF in Preview, and then go to <em>File &gt; Print</em>. We'll not
                    be printing the PDF, but instead save it out as a new PDF.
                    </p>
                    <p>
                    Under <em>Paper Size</em>, select <em>Manage Custom Sizes</em>. We're going to
                    create a custom paper size, so click the plus button at the bottom of the list.
                    </p>
                    <p>
                    Depending on whether your slides are widescreen or not, set your new paper to
                    the following sizes.
                    </p>
                    <table style="width:500px;height:71px">
                    <tbody>
                        <tr>
                        <th style="width:146px">Aspect</th>
                        <th style="width:98.5625px">Width</th>
                        <th style="width:101.4375px">Height</th>
                        </tr>
                        <tr>
                        <td style="width:146px">Widescreen &nbsp;</td>
                        <td style="width:98.5625px">960mm &nbsp;</td>
                        <td style="width:101.4375px">540mm &nbsp;</td>
                        </tr>
                        <tr>
                        <td style="width:146px">4:3 &nbsp;</td>
                        <td style="width:98.5625px">640mm &nbsp;</td>
                        <td style="width:101.4375px">480mm &nbsp;</td>
                        </tr>
                    </tbody>
                    </table>
                    <p>
                    Give your new paper size a name (something like "Slides widescreen" or "Slides
                    4:3" might be helpful next time) and OK the changes.
                    </p>
                    <p>
                    If the preview looks good, in the PDF dropdown in the bottom left, select the
                    <em>Save As PDF</em> option and save your new file.
                    </p>
                    <h4>Upload your new PDF</h4>
                    <p>
                    Now that you have a nice resized PDF, upload it to Notist. Hopefully the results
                    will be much better.
                    </p>
                    <h3 class="block-title" id="slide-download">Making slides available for download</h3>
                    <p>
                    You can make the original slide deck that you uploaded available for visitors
                    to download by checking the checkbox on the Slidedeck page for that presentation.
                    This will create a link under your slides that will download the PDF.
                    </p>
                    <p>
                    Note that this enables the download of the
                    <strong>original PDF that you uploaded</strong>, not a recreated deck with additional
                    information added via Notist.
                    </p>
                    <h3 class="block-title" id="resources">Adding resources</h3>
                    <p>
                    Resources can be added to a presentation. If you have any external links that
                    you would link to add then add them here and they will appear on the presentation
                    page for visitors to access.
                    </p>
                    <h3 class="block-title" id="tweets">Adding tweets</h3>
                    <p>
                    You can add relevant tweets to your presentation vis the Tweets tab. We will
                    be extending this functionality in future. For now, add the URL on an individual
                    tweet and we will retrieve and embed the tweet to the page for this presentation.
                    </p>
                </div>
            </section>
            <section id="events" class="doc-section">
                <h2 class="section-title">Managing events</h2>
                <div class="section-block">
                    <h3 class="block-title" id="add-event">Adding a new event</h3>
                    <p>
                    Events typically get added when a presentation is created. If we can't find an
                    event in the location and at the date and time you enter, we will ask you for
                    the title of the event in order to create it.
                    </p>
                    <p>
                    As the person who created an event you will also be able to edit the other details.
                    </p>
                    <p>
                    Events can also be added outside of the Presentation creation process. Add an
                    event at this link and, as with the account creation process we will check to
                    see if it already exists before creating it.
                    </p>
                </div>
            </section>
        </div>
    </div>
    <div class="doc-sidebar col-md-3 col-12 order-0 d-none d-md-flex">
        <div id="doc-nav" class="doc-nav">  
                <nav id="doc-menu" class="nav doc-menu flex-column sticky">
                    <a class="nav-link scrollto" href="#presentations">Presentations</a>
                    <nav class="doc-sub-menu nav flex-column">
                        <a class="nav-link scrollto" href="#add-presentation">Adding a new presentation</a>
                        <a class="nav-link scrollto" href="#add-slidedeck">Adding a slide deck</a>
                        <a class="nav-link scrollto" href="#two-pdfs">Why two PDFs?</a>
                        <a class="nav-link scrollto" href="#image-quality">Getting the best image quality</a>
                        <a class="nav-link scrollto" href="#slide-download">Making slides available for download</a>
                        <a class="nav-link scrollto" href="#resources">Adding resources</a>
                        <a class="nav-link scrollto" href="#tweets">Adding tweets</a>
                    </nav>
                    <a class="nav-link scrollto" href="#events">Events</a>
                    <nav class="doc-sub-menu nav flex-column">
                        <a class="nav-link scrollto" href="#add-event">Adding a new event</a>
                    </nav>
                    <a class="nav-link scrollto" href="#pro">Pro accounts</a>
                    <a class="nav-link scrollto" href="#general">General</a>
                    <a class="nav-link scrollto" href="#import-export">Importing and exporting</a>
                </nav>
        </div>
    </div>
</div>