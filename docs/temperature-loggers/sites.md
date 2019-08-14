
List of Temperature Logger Sites
================================

The list of sites for *AIMS Temperature Loggers* is:

<div id="sites"></div>

<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="../js/script.js"></script>
<script>

$.get("https://6aq0l8l806.execute-api.ap-southeast-2.amazonaws.com/prod/v1.0/10.25845/5b4eb0f9bb848/sites")
.done(populateTempLoggerSites);

function populateTempLoggerSites(data) { populate("Sites", "sites", data.results); }

</script>
