---
layout: docs
title: Orange accordion
group: components
---

Extend the default collapse behavior to create an accordion with the panel component.

### Default accordion

{% example html %}
<div class="o-accordion panel-group" id="accordion-1" role="tablist" aria-multiselectable="true">
    <div class="panel panel-default">
        <div class="panel-heading" role="tab" id="headingOne">
            <h4 class="panel-title">
                <a data-toggle="collapse" data-parent="#accordion-1" href="#collapseOne"> Collapsible Group Item #1 </a>
            </h4>
        </div>
        <div id="collapseOne" class="panel-collapse collapse in">
            <div class="panel-body">Anim pariatur cliche reprehenderit,
                enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                moon officia aute, non cupidatat <a href="#">test focus 1</a> skateboard dolor brunch. Food
                truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                sunt aliqua put a bird on it squid single-origin coffee nulla
                assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                labore wes anderson cred nesciunt <a href="#">test focus 2</a> sapiente ea proident. Ad vegan
                excepteur butcher vice lomo. Leggings occaecat craft beer
                farm-to-table, raw denim aesthetic synth nesciunt you probably
                haven't heard of them accusamus labore sustainable VHS.</div>
        </div>
    </div>
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title" id="accordion-1-title-2">
                <a class="collapsed" data-toggle="collapse" data-parent="#accordion-1" href="#collapseTwo"> Collapsible Group Item #2 </a>
            </h4>
        </div>
        <div id="collapseTwo" class="panel-collapse collapse">
            <div class="panel-body">Anim pariatur cliche reprehenderit,
                enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                moon officia aute, non cupidatat skateboard dolor brunch. Food
                truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                sunt aliqua put a bird on it squid single-origin coffee nulla
                assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                labore wes anderson cred nesciunt sapiente ea proident. Ad vegan <a href="#">test focus 3</a>
                excepteur butcher vice lomo. Leggings occaecat craft beer
                farm-to-table, raw denim aesthetic synth nesciunt you probably
                haven't heard of them accusamus labore sustainable VHS.</div>
        </div>
    </div>
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title" id="accordion-1-title-3">
                <a class="collapsed" data-toggle="collapse" data-parent="#accordion-1" href="#collapseThree"> Collapsible Group Item #3 </a>
            </h4>
        </div>
        <div id="collapseThree" class="panel-collapse collapse">
            <div class="panel-body">Anim pariatur cliche reprehenderit,
                enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                moon officia aute, non cupidatat skateboard dolor brunch. Food
                truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                sunt aliqua put a bird on it squid single-origin coffee nulla
                assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                labore wes anderson cred nesciunt sapiente ea proident. Ad vegan
                excepteur butcher vice lomo. Leggings occaecat craft beer
                farm-to-table, raw denim aesthetic synth nesciunt you probably
                haven't heard of them accusamus labore sustainable VHS.</div>
        </div>
    </div>
</div>
{% endexample %}

### Mulitple openable

{% example html %}
<div class="o-accordion panel-group" id="accordion-2">
        <div class="panel panel-default">
            <div class="panel-heading">
                <h4 class="panel-title" id="accordion-2-title-1">
                    <a class="" data-toggle="collapse" href="#collapse2One"> Collapsible Group Item #1 </a>
                </h4>
            </div>
            <div id="collapse2One" class="panel-collapse collapse in">
                <div class="panel-body">Anim pariatur cliche reprehenderit,
                    enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                    moon officia aute, non cupidatat <a href="#">test focus 1</a> skateboard dolor brunch. Food
                    truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                    sunt aliqua put a bird on it squid single-origin coffee nulla
                    assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                    labore wes anderson cred nesciunt <a href="#">test focus 2</a> sapiente ea proident. Ad vegan
                    excepteur butcher vice lomo. Leggings occaecat craft beer
                    farm-to-table, raw denim aesthetic synth nesciunt you probably
                    haven't heard of them accusamus labore sustainable VHS.</div>
            </div>
        </div>
        <div class="panel panel-default">
            <div class="panel-heading">
                <h4 class="panel-title" id="accordion-2-title-2">
                    <a class="collapsed" data-toggle="collapse" href="#collapse2Two"> Collapsible Group Item #2 </a>
                </h4>
            </div>
            <div id="collapse2Two" class="panel-collapse collapse">
                <div class="panel-body">Anim pariatur cliche reprehenderit,
                    enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                    moon officia aute, non cupidatat skateboard dolor brunch. Food
                    truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                    sunt aliqua put a bird on it squid single-origin coffee nulla
                    assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                    labore wes anderson cred nesciunt sapiente ea proident. Ad vegan <a href="#">test focus 3</a>
                    excepteur butcher vice lomo. Leggings occaecat craft beer
                    farm-to-table, raw denim aesthetic synth nesciunt you probably
                    haven't heard of them accusamus labore sustainable VHS.</div>
            </div>
        </div>
        <div class="panel panel-default">
            <div class="panel-heading">
                <h4 class="panel-title" id="accordion-2-title-3">
                    <a class="collapsed" data-toggle="collapse" href="#collapse2Three"> Collapsible Group Item #3 </a>
                </h4>
            </div>
            <div id="collapse2Three" class="panel-collapse collapse">
                <div class="panel-body">Anim pariatur cliche reprehenderit,
                    enim eiusmod high life accusamus terry richardson ad squid. 3 wolf
                    moon officia aute, non cupidatat skateboard dolor brunch. Food
                    truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
                    sunt aliqua put a bird on it squid single-origin coffee nulla
                    assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer
                    labore wes anderson cred nesciunt sapiente ea proident. Ad vegan
                    excepteur butcher vice lomo. Leggings occaecat craft beer
                    farm-to-table, raw denim aesthetic synth nesciunt you probably
                    haven't heard of them accusamus labore sustainable VHS.</div>
            </div>
        </div>
    </div>
{% endexample %}