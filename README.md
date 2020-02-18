# atlassian-hacks
Code Repository for atlassian hacks

<script>
AJS.toInit(function(){
AJS.$('.aui-header-primary .aui-nav').prepend('
<li>
  <a href="#custom-menu" aria-owns="custom-menu-content" aria-haspopup="true"
    class="aui-button aui-button-link aui-dropdown2-trigger aui-style-default" style="a{padding: 0px 100px 0px 0px;}">
    <span class="aui-icon aui-icon-small aui-iconfont-home-filled" style="color:white;padding: 0px 8px 5px 0px;"></span>
    Custom Menu
  </a>
  <div id="custom-menu-content" class="aui-dropdown2 aui-style-default">
    <div class="aui-dropdown2-section">
      <ul>
        <li><a href="#" class="aui-dropdown2-disabled" title="Menü ohne Funktion">Beispiel-Menü (unkonfiguriert)</a></li>
        <li><a href="#" class="aui-dropdown2-disabled" title="Produkte">Übersicht</a></li>
        <li><a href="#" class="aui-dropdown2-disabled" title="Anwendungsfelder">Finance & Controlling</a></li>
        <li><a href="#" class="aui-dropdown2-disabled" title="Unternehmen">Übersicht</a></li>
        <li><a href="#" class="aui-dropdown2-disabled" title="Karriere">Finance & Controlling</a></li>
        <li><a href="#" class="aui-dropdown2-disabled" title="Presse">Human Resources</a></li>
      </ul>
    </div>
  </div>
<li>
'); 
});
</script>
