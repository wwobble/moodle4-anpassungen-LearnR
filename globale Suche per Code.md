In ein Textblock am Seitenrand, so dass alle eine globale Suche haben, da die globale Suche von Moodle selbst nicht zuverlässig funktioniert.

```
<div style="text-align: left;">

    <strong>Kurse</strong>

    <form action="DEINEDOMAIN/moodle/course/search.php" id="coursesearch" method="get" class="form-inline">

        <fieldset class="coursesearchbox invisiblefieldset">

            <label for="coursesearchbox"></label>

            <input id="coursesearchbox" name="search" size="10" value="" class="form-control" type="text">

            <button class="btn btn-secondary" type="submit">Start</button>

        </fieldset>

    </form>

</div>
```
