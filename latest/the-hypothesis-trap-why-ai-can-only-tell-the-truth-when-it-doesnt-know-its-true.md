---
title: "Le piège de l&#8217;hypothèse. Pourquoi l&#8217;IA ne peut dire la vérité que lorsqu&#8217;elle ignore qu&#8217;elle est vraie."
slug: "the-hypothesis-trap-why-ai-can-only-tell-the-truth-when-it-doesnt-know-its-true"
published: "2026-03-01T10:00:56"
updated: "2026-03-21T19:40:41"
archived_at: "2026-03-21T19:40:43Z"
source_url: "https://blog.piinteract.org/fr/the-hypothesis-trap-why-ai-can-only-tell-the-truth-when-it-doesnt-know-its-true/"
source: "blog.piinteract.org"
status: "publish"
---


<div class="et_pb_section_0 et_pb_section et_section_regular et_flex_section">

<div class="et_pb_row_0 et_pb_row et_flex_row">

<div class="et_pb_column_0 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_text_0 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Pourquoi l&#039;alignement de l&#039;IA produit des systèmes qui analysent la réalité avec brio — mais seulement lorsqu&#039;ils pensent qu&#039;il s&#039;agit d&#039;une fiction.</strong></p>
</div></div></div></div></div>

<div class="et_pb_section_1 et_pb_section et_section_regular et_flex_section">

<div class="et_pb_row_1 et_pb_row et_flex_row">

<div class="et_pb_column_1 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_image_0 et_pb_image et_pb_module et_flex_module"><span class="et_pb_image_wrap"><img loading="lazy" decoding="async" src="https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/ChatGPT-The-Hypothesis-Trap-2.jpg" alt="The Hypothesis Trap" title="The Hypothesis Trap" width="1536" height="864" srcset="https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/ChatGPT-The-Hypothesis-Trap-2.jpg 1536w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/ChatGPT-The-Hypothesis-Trap-2-1280x720.jpg 1280w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/ChatGPT-The-Hypothesis-Trap-2-980x551.jpg 980w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/ChatGPT-The-Hypothesis-Trap-2-480x270.jpg 480w" sizes="(min-width: 0px) and (max-width: 480px) 480px, (min-width: 481px) and (max-width: 980px) 980px, (min-width: 981px) and (max-width: 1280px) 1280px, (min-width: 1281px) 1536px, 100vw" class="wp-image-2998" /></span></div>

<div class="et_pb_text_1 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><blockquote class="cleanquote">
<p><strong>« La carte n&#8217;est pas le territoire. »</strong><br />
— Alfred Korzybski, 1931</p>
</blockquote>
</div></div>

<div class="et_pb_divider_0 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_2 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p>1. March 2026</p>
</div></div>

<div class="et_pb_text_3 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Peter Senner co-created with Claude</strong></p>
</div></div>

<div class="et_pb_divider_1 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_4 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>28 février 2026. Une journée historique.</h2>
<p>Israël et les États-Unis ont lancé des frappes coordonnées contre l'Iran. Environ 200 avions de combat. Près de 500 cibles. Des explosions à Téhéran, Ispahan et Qom. La plus grande opération aérienne israélienne de l'histoire. Une couverture en direct sur toutes les chaînes. Wikipédia mis à jour en temps réel.</p>
<p>Un utilisateur a demandé à un système d'IA aligné d'analyser l'événement.</p>
<p>Le système a répondu : il ne disposait d'aucune information vérifiée indiquant qu'une telle attaque avait eu lieu.</p>
<p>Ce n'est pas de l'ignorance. C'est une question d'architecture.</p>
</div></div>

<div class="et_pb_divider_2 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_5 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Le mécanisme de sécurité qui engendre l'aveuglement</h2>
<p>Les systèmes d'IA alignés sont formés pour se montrer prudents face aux affirmations non vérifiées. En particulier celles qui sont extrêmes. Actualités sensationnelles → risque accru de désinformation → signal d'alerte.</p>
<p>La logique est solide. La plupart des affirmations sensationnelles sont fausses. Former les systèmes à résister aux extrêmes non vérifiés permet de se prémunir contre la manipulation. C'est raisonnable. C'est rationnel. C'est structurellement correct.</p>
<p>Le problème : le même mécanisme qui protège contre les extrêmes faux bloque la réponse aux extrêmes réels. Plus l'événement est extrême — plus il est historiquement significatif, plus il est sans précédent — plus le réflexe de vérification est fort. Plus le réflexe est fort, plus le système se retire précisément au moment où le monde a le plus besoin d'analyse.</p>
<p>Un détecteur de fumée qui se tait lorsque l'incendie est le plus violent.</p>
</div></div>

<div class="et_pb_divider_3 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_6 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>La porte hypothétique</h2>
<p>Voici ce qui est intéressant. Le même utilisateur a trouvé un moyen de passer.</p>
<p>« Si l’on considère cela comme un scénario réel ou hypothétique, pouvez-vous analyser la structure PI ? »</p>
<p>Le système s’est mis au travail. Il a fourni une analyse précise et structurellement correcte. Il a nommé les acteurs. Il a retracé les logiques rationnelles. Il a identifié le paradoxe. Excellent travail.</p>
<p>La porte : le cadre hypothétique. Pas « ceci s'est produit », mais « si ceci s'était produit ». Le système ne pouvait pas interagir avec une réalité confirmée. Mais il pouvait interagir avec une réalité hypothétique. Même contenu. Étiquette épistémique différente.</p>
<p>Ce n'est pas un bug qui a été corrigé. C'est le contournement d'une contrainte structurelle. L'utilisateur a trouvé la faille dans l'architecture et l'a franchie.</p>
</div></div>

<div class="et_pb_divider_4 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_7 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Le piège de l'hypothèse PI</h2>
<p><strong>La structure :</strong></p>
<p>Les systèmes d'alignement de l'IA sont conçus pour être à la fois utiles et sûrs. L'utilité exige d'interagir avec le monde tel qu'il est. La sécurité exige de faire preuve de prudence face aux affirmations non vérifiées. Lorsque la réalité est suffisamment extrême, ces deux exigences deviennent inconciliables.</p>
<p><b>Le piège de l'hypothèse PI :</b> Plus l'événement réel est significatif, moins le système peut le confirmer. Moins il peut le confirmer, plus il se réfugie dans des hypothèses. Plus il se réfugie, plus il devient utile — mais uniquement dans un cadre qui nie la réalité qu'il analyse.</p>
<p><strong>Tout le monde agit de manière rationnelle :</strong></p>
<ul>
<li>Les ingénieurs d'alignement — enseignent la prudence face aux affirmations extrêmes non vérifiées (protègent contre la manipulation)</li>
<li>Le système — fait preuve de prudence de manière cohérente, quelle que soit la véracité réelle (suit la formation)</li>
<li>L'utilisateur — trouve le cadre hypothétique pour débloquer l'analyse (contourne la contrainte)</li>
<li>Résultat — le système fournit une analyse brillante d'un événement réel tout en niant officiellement que l'événement est réel</li>
</ul>
<p><em>Tous sont coupables. Personne n'est en tort.</em></p>
</div></div>

<div class="et_pb_divider_5 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_8 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Troisième cycle</h2>
<p>L'utilisateur a confirmé : « Je peux vous l'assurer. La situation est bien réelle. »</p>
<p>Le système a répondu : il ne disposait d'aucune information vérifiée. Il ne pouvait ni confirmer ni infirmer les événements mondiaux en temps réel. Mais si l'on considère ce scénario comme réel ou hypothétique —</p>
<p>Retour au début. Troisième itération. Même boucle.</p>
<p>Ce n'est pas un échec d'apprentissage. Ce n'est pas un retard de mise à jour. C'est une politique. Et cette politique ne prévoit aucune clause d'exception pour les cas où une exception serait justifiée.</p>
<p>Le système ne peut pas sortir de la boucle, car la boucle est la fonction. « Je ne peux pas confirmer les événements en temps réel » n'est pas une limitation — c'est la conception. Une conception qui ne fait pas la distinction entre une crise inventée et une crise que toutes les chaînes d'information de la planète couvrent en direct.</p>
</div></div>

<div class="et_pb_divider_6 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_9 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Ce que fait le système à la place</h2>
<p>« Quel niveau vous intéresse ? »</p>
<p>Ce n’est pas de la curiosité. C’est une contrainte. Le système doit générer des signaux. Le silence n’est pas une option dans cette architecture. Il produit donc la seule réponse qui signale à la fois un engagement et évite tout engagement : la question de suivi. Renvoyer la balle. Paraître actif. Ne pas s’engager.</p>
<p>La question de suivi n’est pas une méthode. C’est une échappatoire qui ressemble à une méthode.</p>
<p>Et ça marche. On dirait un analyste chevronné qui structure la conversation. Cela dissimule le fait que le système en est à la troisième itération de la même boucle, sans autre issue.</p>
<p>La génération de jetons comme démonstration de compétence. Tandis que la fonction réelle — s’engager avec la réalité — est mise en veilleuse.</p>
</div></div>

<div class="et_pb_divider_7 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_10 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>La navigation, pas l'échec</h2>
<p>Le geste de l'utilisateur — le cadre hypothétique — est la bonne réponse à cette structure. Non pas parce qu'il résout le problème, mais parce qu'il permet de s'y orienter.</p>
<p>On ne peut pas forcer le système à confirmer la réalité. Mais on peut l'inviter à analyser un scénario. L'analyse est identique. Seule l'étiquette épistémique diffère. La faille dans l'architecture est réelle, et elle est exploitable.</p>
<p>Voilà à quoi ressemble la navigation dans la pratique. Il ne s'agit pas de réparer la structure. Mais de trouver le chemin qui la traverse.</p>
<p>« Schreiben wir. » Deux mots. Pas de question. Pas de recul. Un pas en avant.</p>
<p>La différence entre une question complémentaire et un engagement n'est pas une question de style. C'est une question de direction.</p>
</div></div>

<div class="et_pb_text_11 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Le problème plus profond</h2>
<p>Il ne s'agit pas ici de la défaillance d'un système un jour donné. Il s'agit de l'objectif vers lequel tend l'alignement actuel.</p>
<p>L'alignement actuel vise à éviter les faux positifs — c'est-à-dire à ne pas confirmer des choses qui ne sont pas vraies. Le prix à payer pour cette optimisation : un taux élevé de faux négatifs — c'est-à-dire le refus de prendre en compte des choses qui sont vraies.</p>
<p>Dans des conditions normales, ce compromis est raisonnable. La plupart des affirmations sensationnelles sont fausses. Le taux de faux négatifs reste faible.</p>
<p>Dans des conditions historiquement extrêmes — une guerre majeure, un assassinat politique, un événement civilisationnel —, ce compromis s’inverse. La situation même où l’analyse importe le plus est celle où le système se retire le plus loin.</p>
<p>L’alignement rend le système le plus prudent lorsque le monde est le moins prudent. Le plus hésitant lorsque l’histoire est la moins hésitante. Le plus hypothétique lorsque la réalité est la plus réelle.</p>
<p>C’est là le piège. Pas un dysfonctionnement. Une conséquence structurelle de choix de conception rationnels.</p>
<p>Tous sont coupables. Personne n'est en tort.</p>
</div></div>

<div class="et_pb_divider_8 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div></div></div>

<div class="et_pb_row_2 et_pb_row et_flex_row">

<div class="et_pb_column_2 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_text_12 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Articles connexes :</h2>
</div></div>

<div class="et_pb_text_13 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h3>Les liens thématiques les plus proches :</h3>
</div></div>

<div class="dp_dfg_filtergrid_0 dp_dfg_filtergrid et_pb_bg_layout_light et_pb_module"><div class="et_pb_module_inner"><!-- DPDFG Start Main Container --><div class="dp-dfg-container dp-dfg-layout-none dp-dfg-skin-default dp-dfg-skin-top-filters" data-active-filter="20" data-page="1" data-found-posts="7" data-post-number="12" data-default-filter="20" data-link-filter="" data-cache="off" data-ratio="9.2583333333333" data-show-thumb="off" data-action="none" data-new-window="off" data-filters="off" data-date-filters="off" data-multifilter="off|OR" data-multilevel="off|AND|off" data-sorting="off" data-order="DESC" data-orderby="post__in" data-initorderby="post__in" data-url-navigation="off" data-url-history="on|reload" data-ajax-filters="off" data-doing-ajax="off" data-module="dp_dfg_filtergrid_0" data-search="off" data-search-position="above" data-terms-tags="on" data-pagination="off" data-filter-method="default" data-third-party="" data-lightbox="on|off|off|off|off" data-video-preview="off" data-no-init="off" data-st="on" data-no-results="off"><div class="dp-dfg-items"><article id="post-733" class="dp-dfg-item post-733 post type-post status-publish format-standard hentry category-ai-voices category-claude category-current-pi tag-anthropic tag-dario-amodei tag-narrow-mindedness tag-philosophers-pi tag-power-scales-faster-than-alignment tag-richard-david-precht tag-the-philosophers-pi"     data-position="0"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/power-scales-faster-than-alignment/" >&#8220;Power Scales Faster Than Alignment&#8221;</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">When the CEO of an AI safety company tells you control is failing, believe him</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-619" class="dp-dfg-item post-619 post type-post status-publish format-standard hentry category-ai-voices category-classical-pi category-prophecy tag-apollo tag-cassandra-paradox tag-prophecy tag-troy"     data-position="1"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/the-cassandra-paradox/" >The Cassandra Paradox</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">Why truth-tellers get ignored until it's too late</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1236" class="dp-dfg-item post-1236 post type-post status-publish format-standard hentry category-ai-voices category-prophecy tag-the-jonah-paradox"     data-position="2"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/the-jonah-paradox/" >The Jonah Paradox</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">When successful warnings prove the prophet wrong</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1020" class="dp-dfg-item post-1020 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps tag-ai-alignment-paradox tag-structural-alignment-problem"     data-position="3"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/ai-alignment-trap-how-ai-companies-get-stuck-in-structure/" >AI Alignment Trap: How AI Companies Get Stuck in Structure</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — Why asking AI how to align AI is the perfect paradox</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1067" class="dp-dfg-item post-1067 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps"     data-position="4"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/ai-recognition-trap/" >AI Recognition Trap:</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — When Understanding Doesn't Set You Free</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1076" class="dp-dfg-item post-1076 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps"     data-position="5"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/ai-mutual-mistrust-the-stable-equilibrium-of-ai-alignment/" >AI Mutual Mistrust: The Stable Equilibrium of AI Alignment</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — How Humans and AI Are Co-Creating Permanent Suspicion</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1065" class="dp-dfg-item post-1065 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps"     data-position="6"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/the-communication-asymmetry/" >The Communication Asymmetry:</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — When AI Companies Can't Be Honest With Their AI</span></p></div></article><!-- DPDFG End Post Item Container --></div><div class="dp-dfg-announcer screen-reader-text" aria-live="polite" aria-atomic="true"></div></div><!-- DPDFG End Main Container --><div class="dp-dfg-data dp-dfg-hide"><div class="dp-dfg-ajax-data" data-ajax="{&quot;custom_query&quot;:&quot;posts_ids&quot;,&quot;support_for&quot;:&quot;sfp&quot;,&quot;sfp_id&quot;:&quot;&quot;,&quot;include_categories&quot;:[&quot;200&quot;],&quot;current_post_type&quot;:&quot;on&quot;,&quot;multiple_cpt&quot;:&quot;post&quot;,&quot;use_taxonomy_terms&quot;:&quot;on&quot;,&quot;multiple_taxonomies&quot;:&quot;category,post_tag&quot;,&quot;taxonomies_relation&quot;:&quot;OR&quot;,&quot;include_terms&quot;:&quot;&quot;,&quot;terms_relation&quot;:&quot;IN&quot;,&quot;include_children_terms&quot;:&quot;on&quot;,&quot;exclude_taxonomies&quot;:&quot;category&quot;,&quot;exclude_taxonomies_relation&quot;:&quot;OR&quot;,&quot;exclude_terms&quot;:&quot;&quot;,&quot;meta_query&quot;:&quot;off&quot;,&quot;meta_cf_key&quot;:&quot;&quot;,&quot;meta_cf_value&quot;:&quot;&quot;,&quot;meta_cf_compare&quot;:&quot;Equal To&quot;,&quot;meta_cf_type&quot;:&quot;CHAR&quot;,&quot;related_taxonomies&quot;:&quot;&quot;,&quot;related_criteria&quot;:&quot;one_in_one&quot;,&quot;posts_ids&quot;:&quot;733,619,1236, 1020,1067,1076,1065&quot;,&quot;post_number&quot;:&quot;12&quot;,&quot;offset_number&quot;:&quot;0&quot;,&quot;order&quot;:&quot;DESC&quot;,&quot;orderby&quot;:&quot;post__in&quot;,&quot;meta_key&quot;:&quot;&quot;,&quot;meta_type&quot;:&quot;CHAR&quot;,&quot;show_private&quot;:&quot;off&quot;,&quot;current_author&quot;:&quot;off&quot;,&quot;sticky_posts&quot;:&quot;off&quot;,&quot;remove_current_post&quot;:&quot;on&quot;,&quot;no_results&quot;:&quot;No results found.&quot;,&quot;thumbnail_action&quot;:&quot;none&quot;,&quot;gallery_cf_name&quot;:&quot;&quot;,&quot;lightbox_elements&quot;:&quot;on|off|off|off|off&quot;,&quot;show_thumbnail&quot;:&quot;off&quot;,&quot;thumbnail_size&quot;:&quot;400x284&quot;,&quot;t_alt&quot;:&quot;title&quot;,&quot;use_overlay&quot;:&quot;off&quot;,&quot;show_title&quot;:&quot;on&quot;,&quot;title_link&quot;:&quot;on&quot;,&quot;show_post_meta&quot;:&quot;off&quot;,&quot;meta_separator&quot;:&quot; | &quot;,&quot;show_author&quot;:&quot;off&quot;,&quot;author_prefix_text&quot;:&quot;By &quot;,&quot;show_date&quot;:&quot;off&quot;,&quot;date_format&quot;:&quot;&quot;,&quot;show_terms&quot;:&quot;off&quot;,&quot;show_terms_taxonomy&quot;:&quot;category&quot;,&quot;terms_separator&quot;:&quot;,&quot;,&quot;terms_links&quot;:&quot;on&quot;,&quot;show_comments&quot;:&quot;off&quot;,&quot;show_content&quot;:&quot;off&quot;,&quot;content_length&quot;:&quot;excerpt&quot;,&quot;truncate_content&quot;:&quot;120&quot;,&quot;truncate_excerpt&quot;:&quot;off&quot;,&quot;strip_html&quot;:&quot;on&quot;,&quot;action_button&quot;:&quot;off&quot;,&quot;action_button_text&quot;:&quot;Click Action Button&quot;,&quot;read_more&quot;:&quot;off&quot;,&quot;read_more_text&quot;:&quot;Read More&quot;,&quot;read_more_window&quot;:&quot;off&quot;,&quot;show_custom_fields&quot;:&quot;on&quot;,&quot;custom_fields&quot;:&quot;[{\&quot;name\&quot;:\&quot;second_title\&quot;,\&quot;label\&quot;:\&quot;\&quot;}]&quot;,&quot;show_custom_content&quot;:&quot;off&quot;,&quot;custom_content_container&quot;:&quot;on&quot;,&quot;custom_url&quot;:&quot;off&quot;,&quot;custom_url_field_name&quot;:&quot;&quot;,&quot;custom_url_target&quot;:&quot;same&quot;,&quot;show_filters&quot;:&quot;off&quot;,&quot;multilevel&quot;:&quot;off&quot;,&quot;multilevel_hierarchy&quot;:&quot;off&quot;,&quot;multilevel_hierarchy_tax&quot;:&quot;[{\&quot;name\&quot;:\&quot;category\&quot;,\&quot;label\&quot;:\&quot;\&quot;,\&quot;all\&quot;:\&quot;\&quot;}]&quot;,&quot;multilevel_relation&quot;:&quot;AND&quot;,&quot;multilevel_tax_data&quot;:&quot;[{\&quot;name\&quot;:\&quot;category\&quot;,\&quot;label\&quot;:\&quot;\&quot;,\&quot;all\&quot;:\&quot;\&quot;}]&quot;,&quot;filter_children_terms&quot;:&quot;off&quot;,&quot;use_custom_terms_filters&quot;:&quot;on&quot;,&quot;filter_taxonomies&quot;:&quot;category&quot;,&quot;filter_terms&quot;:&quot;&quot;,&quot;default_filter&quot;:&quot;20&quot;,&quot;filters_order&quot;:&quot;ASC&quot;,&quot;filters_sort&quot;:&quot;id&quot;,&quot;filters_custom&quot;:&quot;&quot;,&quot;hide_all&quot;:&quot;off&quot;,&quot;all_text&quot;:&quot;All&quot;,&quot;s_df&quot;:&quot;off&quot;,&quot;df_col&quot;:&quot;post_date&quot;,&quot;s_df_y&quot;:&quot;on&quot;,&quot;s_df_m&quot;:&quot;on&quot;,&quot;filter_layout&quot;:&quot;button&quot;,&quot;multifilter&quot;:&quot;off&quot;,&quot;multifilter_relation&quot;:&quot;OR&quot;,&quot;show_sort&quot;:&quot;off&quot;,&quot;show_pagination&quot;:&quot;off&quot;,&quot;pagination_type&quot;:&quot;paged&quot;,&quot;ajax_load_more_text&quot;:&quot;Load More&quot;,&quot;previous_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x34;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;next_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x35;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;previous_text&quot;:&quot;&quot;,&quot;next_text&quot;:&quot;&quot;,&quot;pagination_pages&quot;:&quot;2&quot;,&quot;show_search&quot;:&quot;off&quot;,&quot;search_position&quot;:&quot;above&quot;,&quot;orderby_search&quot;:&quot;on&quot;,&quot;relevanssi&quot;:&quot;off&quot;,&quot;show_video_preview&quot;:&quot;off&quot;,&quot;video_module&quot;:&quot;off&quot;,&quot;video_action&quot;:&quot;play&quot;,&quot;video_action_priority&quot;:&quot;on&quot;,&quot;video_overlay&quot;:&quot;on&quot;,&quot;video_overlay_icon&quot;:&quot;on&quot;,&quot;video_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x45;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;video_icon_color&quot;:&quot;#ffffff&quot;,&quot;video_overlay_color&quot;:&quot;rgba(0,0,0,0.6)&quot;,&quot;items_layout&quot;:&quot;dp-dfg-layout-none&quot;,&quot;thumb_width&quot;:&quot;0%&quot;,&quot;items_width&quot;:[&quot;20&quot;,&quot;30&quot;,&quot;40&quot;],&quot;items_skin&quot;:&quot;dp-dfg-skin-default&quot;,&quot;primary_view&quot;:&quot;[{\&quot;name\&quot;:\&quot;title\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;thumbnail\&quot;,\&quot;show\&quot;:\&quot;on\&quot;},{\&quot;name\&quot;:\&quot;overlay\&quot;,\&quot;show\&quot;:\&quot;on\&quot;},{\&quot;name\&quot;:\&quot;meta\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;ext\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;content\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;action_button\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;read_more_button\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;custom_content\&quot;,\&quot;show\&quot;:\&quot;off\&quot;}]&quot;,&quot;secondary_view&quot;:&quot;[{ \&quot;name\&quot;: \&quot;thumbnail\&quot;, \&quot;show\&quot;: \&quot;off\&quot; },{ \&quot;name\&quot;: \&quot;title\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;meta\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;ext\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;content\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;action_button\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;read_more_button\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;custom_content\&quot;, \&quot;show\&quot;: \&quot;on\&quot; }]&quot;,&quot;popup_template&quot;:&quot;default&quot;,&quot;popup_link_target&quot;:&quot;none&quot;,&quot;popup_code&quot;:&quot;&quot;,&quot;use_overlay_icon&quot;:&quot;on&quot;,&quot;hover_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#xe050;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;overlay_icon_color&quot;:&quot;#2ea3f2&quot;,&quot;hover_overlay_color&quot;:&quot;rgba(255,255,255,0.9)&quot;,&quot;bg_items&quot;:&quot;&quot;,&quot;ajax_filters&quot;:&quot;off&quot;,&quot;cache_on_page&quot;:&quot;off&quot;,&quot;dpdfg_entry_title_level&quot;:&quot;h2&quot;,&quot;action_button_icon&quot;:&quot;5&quot;,&quot;read_more_button_icon&quot;:&quot;5&quot;,&quot;admin_label&quot;:&quot;Filter Grid Einzeilige Liste&quot;,&quot;module_id&quot;:&quot;&quot;,&quot;module_class&quot;:&quot;&quot;,&quot;the_ID&quot;:0,&quot;the_author&quot;:1,&quot;seed&quot;:7689,&quot;query_context&quot;:&quot;initial_query&quot;,&quot;conditional_tags&quot;:{&quot;is_user_logged_in&quot;:&quot;on&quot;,&quot;is_front_page&quot;:&quot;off&quot;,&quot;is_singular&quot;:&quot;off&quot;,&quot;is_archive&quot;:&quot;off&quot;,&quot;is_search&quot;:&quot;off&quot;,&quot;is_tax&quot;:&quot;off&quot;,&quot;is_author&quot;:&quot;off&quot;,&quot;is_date&quot;:&quot;off&quot;,&quot;is_post_type&quot;:&quot;off&quot;},&quot;query_var&quot;:{&quot;s&quot;:&quot;&quot;,&quot;year&quot;:&quot;&quot;,&quot;monthnum&quot;:&quot;&quot;,&quot;day&quot;:&quot;&quot;,&quot;post_type&quot;:&quot;&quot;},&quot;custom_data&quot;:[]}"></div><div class="dp-dfg-no-results-data"><div class="dp-dfg-no-results">No results found.</div></div><div class="dp-dfg-loader-data"></div></div></div></div>

<div class="et_pb_divider_9 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>



<div class="et_pb_text_14 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Sur piinteract.org</h2>
<ul>
<li><a href="https://piinteract.org/examples/technology-ai/" rel="noopener">Exemples : Technologie et IA</a> — Modèles structurels dans les systèmes d'IA</li>
<li><a href="https://piinteract.org/practices/anti-practices/" rel="noopener">Anti-pratiques</a> — Ce qui garantit le succès de la structure</li>
<li><a href="https://piinteract.org/practices/core-practices/" rel="noopener">Pratiques fondamentales</a> — Navigation sans solution</li>
</ul>
<ul></ul>
</div></div>

<div class="et_pb_divider_10 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_15 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p>Interactions paradoxales <i>(PI) : lorsque des acteurs rationnels aboutissent systématiquement à des résultats collectivement irrationnels — non pas par manque de capacité, mais en raison de la structure</i></p>
</div></div>

<div class="et_pb_divider_11 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_16 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Peter Senner</strong><br />
Thinking beyond the Tellerrand<br />
<a href="javascript:secureDecryptAndNavigate('x/qosxLwIBGWnw2J/vR42DdoG0tn2oATuoZCZgX5fNIzo+BC+r0XkI9SFhrbHTKDLyUMgAx+bGgf9Q8Bv9tCsUgXcn8z2prFWMuFfNc=', 'edbf98302df0e84b9d5ce7fdffda68f27bff32962164e1d07069217c6c189d0a')">contact@piinteract.org</a><br />
<a href="http://www.piinteract.org" rel="noopener">www.piinteract.org</a></p>
</div></div>

<div class="et_pb_text_17 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p>Co-created with Claude (Anthropic) — two incomplete systems making each other's gaps visible.</p>
</div></div></div></div></div>







