---
layout: default
---

<b>Content:</b>

{% for item in site.contributions %}
<ul><li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></li></ul>
{% endfor %}

<div class="panel panel-default">
<div class="panel-body">
First published in the United Kingdom in 2015. Published by Uniform Communications Ltd. © Uniform Communications Ltd, 2015.
<br />All Rights Reserved. No part of this publication may be reproduced or transmitted in any form or by any means; electric or mechanical, including photocopy, recording, or any other information storage and retrieval system without prior permission in writing from the publisher.
</div>
<div class="panel-footer">

ISBN : 978-0-9576868-4-7
<br />Printed in Great Britain.

<br />Edited by
<br />Irini Papadimitriou, Andrew Prescott and Jon Rogers

<br />Design by
<br />uniform.net
</div>
</div>
