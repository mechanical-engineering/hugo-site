+++
title = "Hugo tricks"
date = "2024-01-18"
tags = [ "dev" ]
topics = [ "" ]
+++

Στο συγκεκριμένο άρθρο θα συγκεντρώνω πληροφορίες σχετικά με το αγαπημενο Hugo, org-mode, emacs και γενικά περί του ιστότοπου και την ανάπτυξη αυτού.


    [ψωμί]({{< ref "post/to-psomi.md" >}})


    C-c C-, ## org-insert-structure-template
     :EXPORT_OPTIONS: toc:nil

     {{&lt; imgur id="vRbDiHJ" &gt;}}
     {{&lt tweet user="" id=""&gt}}
     { {< tweet user="xoriopalio" id="">}}
     <figure>
       <a href="https://unsplash.com/photos/purple-petaled-flowers-0ZxdAGG4aWU">
         <img src="https://images.unsplash.com/photo-1534710961216-75c88202f43e?q=80&w=1976&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" height="600" widht=""300">
       </a>
     </figure>


     author = "Argiris_G"

Do a paste 【Ctrl+y】.
Press 【Alt+y】 to swap the paste content from previous entry.
Repeat 【Alt+y】 for earlier content.

**Details**

{{< details "This is the details title (click)" >}}
This is the content (hidden until clicked).
{{< /details >}}
