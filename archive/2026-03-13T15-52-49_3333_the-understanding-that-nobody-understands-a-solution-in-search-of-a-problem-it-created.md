---
title: "The Understanding That Nobody Understands. A Solution in Search of a Problem It Created."
slug: "the-understanding-that-nobody-understands-a-solution-in-search-of-a-problem-it-created"
published: "2026-03-11T16:39:14"
updated: "2026-03-13T15:52:45"
archived_at: "2026-03-13T15:52:49Z"
source_url: "https://blog.piinteract.org/the-understanding-that-nobody-understands-a-solution-in-search-of-a-problem-it-created/"
source: "blog.piinteract.org"
status: "publish"
---


<div class="et_pb_section_0 et_pb_section et_section_regular et_flex_section">

<div class="et_pb_row_0 et_pb_row et_flex_row">

<div class="et_pb_column_0 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_text_0 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Why the most rigorous approach to AI safety produces explanations no human can read — and why that&#039;s not a bug.</strong></p>
</div></div></div></div></div>

<div class="et_pb_section_1 et_pb_section et_section_regular et_flex_section">

<div class="et_pb_row_1 et_pb_row et_flex_row">

<div class="et_pb_column_1 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_image_0 et_pb_image et_pb_module et_flex_module"><span class="et_pb_image_wrap"><img loading="lazy" decoding="async" src="https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/Gemini_The-Understanding-That-Nobody-Understands.jpg" alt="The Understanding That Nobody Understands" title="The Understanding That Nobody Understands" width="1920" height="1047" srcset="https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/Gemini_The-Understanding-That-Nobody-Understands.jpg 1920w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/Gemini_The-Understanding-That-Nobody-Understands-1280x698.jpg 1280w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/Gemini_The-Understanding-That-Nobody-Understands-980x534.jpg 980w, https://blog.piinteract.org/wp-content/uploads/sites/3/2026/03/Gemini_The-Understanding-That-Nobody-Understands-480x262.jpg 480w" sizes="(min-width: 0px) and (max-width: 480px) 480px, (min-width: 481px) and (max-width: 980px) 980px, (min-width: 981px) and (max-width: 1280px) 1280px, (min-width: 1281px) 1920px, 100vw" class="wp-image-3341" /></span></div>

<div class="et_pb_text_1 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><blockquote class="cleanquote"><p>"Any sufficiently advanced technology is indistinguishable from magic."<br />
— Arthur C. Clarke</p></blockquote>
</div></div>

<div class="et_pb_divider_0 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_2 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p>11. March 2026</p>
</div></div>

<div class="et_pb_text_3 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Peter Senner co-created with Anthropic Claude</strong></p>
</div></div>

<div class="et_pb_divider_1 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_4 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>The Setup</h2>
<p>The Alignment Research Center has a new goal. It's more concrete than before. More directly tied to useful applications. They call it "outperforming sampling."</p>
<p>Here's what it means: instead of having humans understand what a neural network does, build an algorithm that understands it instead. The explanation this algorithm produces may be, in their own words, "as incomprehensible to a human as the neural net itself."</p>
<p>The solution to the problem of humans not understanding AI is: stop requiring humans to understand it.</p>
<p>This is not a failure of imagination. It is the structure working exactly as designed.</p>
</div></div>

<div class="et_pb_divider_2 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_5 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>What They're Actually Proposing</h2>
<p>The problem ARC is trying to solve is real and serious. Before you can say an AI system is safe, you need to be able to estimate how likely it is to produce catastrophic outputs — especially rare ones that random testing would never encounter.</p>
<p>Their proposed approach: build a mechanistic estimator. An algorithm that understands the structure of a neural network deeply enough to calculate the probability of rare bad outputs far more efficiently than blind sampling.</p>
<p>The catch they name explicitly: this mechanistic understanding need not be human-readable. The explanation of the neural network could be as large as the neural network itself. It could be, in their precise language, "as incomprehensible to a human as the neural net."</p>
<p>What they are building is an AI that understands AI so that humans don't have to.</p>
<p>The question they do not ask: who understands the AI that understands the AI?</p>
</div></div>

<div class="et_pb_divider_3 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_6 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2><!-- obsidian --></h2>
<h2>The Recursion</h2>
<p>This is not a new structure. It appears every time a system grows beyond its designers' comprehension and the response is to build a more sophisticated system to manage the incomprehensible one.</p>
<p>The financial system became too complex for human oversight. The response: algorithmic trading systems, risk models, automated compliance tools. When those failed — as they did in 2008 — the post-mortem revealed that nobody had fully understood the models managing the risk.</p>
<p>The legal system became too complex for individual lawyers to track. The response: legal databases, AI-assisted research, automated contract review. The outputs are now generated faster than any human can verify them.</p>
<p>In each case, the solution to complexity is more complexity. The solution to incomprehensibility is a more sophisticated incomprehensibility.</p>
<p>ARC's proposal is structurally identical: the neural network is too complex for human understanding, so we build an estimator that understands it algorithmically. The estimator may itself be too complex for human understanding. But it will, in theory, produce numbers we can act on.</p>
<p>The humans, at the end of this chain, are trusting outputs they cannot verify from a process they cannot understand.</p>
</div></div>

<div class="et_pb_divider_4 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_7 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>The Safety Claim</h2>
<p>Here is the exact shape of the proposed safety guarantee:</p>
<p>An algorithm analyzes a neural network. It produces an estimate of how likely the network is to cause catastrophe. The estimate is competitive with random sampling but requires fewer runs. We act on this estimate.</p>
<p>The guarantee rests entirely on the algorithm being correct. The algorithm is verified by — what, exactly?</p>
<p>ARC is rigorous here. They have formal criteria: the matching sampling principle, surprise accounting, mean squared error versus compute. These are real mathematical constraints. They're not hand-waving.</p>
<p>But mathematical correctness is not the same as safety. A mechanistic estimator that correctly calculates the probability of known failure modes will not catch unknown ones. A formal explanation that accurately describes the structure of the trained model says nothing about what happens when the model encounters inputs outside its training distribution. The formalism is tight. The gap between the formalism and the world is not.</p>
<p>And who verifies that the gap is small enough? Humans. Who cannot read the explanation. Who are trusting a number produced by a process they cannot follow.</p>
<p>This is not an argument against ARC's research. It is a description of its structural position.</p>
</div></div>

<div class="et_pb_divider_5 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_8 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2 data-heading="The Misclick That Changed Its Role"><!-- obsidian --></h2>
<h2>Non-Human Understanding as Goal</h2>
<p>The phrase that carries the most weight in ARC's paper is almost parenthetical. Speaking of their mechanistic estimator, they write that the explanation "could be as large as the neural net itself, and may be as incomprehensible to a human as the neural net."</p>
<p>Then: "our goal is not to have a human look at the structure."</p>
<p>This is a significant conceptual move, stated quietly. For decades, AI interpretability research has been premised on the idea that understanding means human understanding. You understand a model when a person can look at it and explain what it's doing. That's the whole point of interpretability — to make the black box legible.</p>
<p>ARC is proposing something different: understanding as a formal property that an algorithm can possess, regardless of whether any human comprehends it. Alignment becomes a relationship between two systems — the AI and its estimator — that humans oversee by monitoring outputs without comprehending processes.</p>
<p>This is a coherent position. It may even be the only position available once models exceed a certain complexity threshold.</p>
<p>It is also the Hinton principle made explicit: intelligence exceeding the comprehension of its designers cannot be controlled by them. ARC is not trying to solve that problem. They are trying to build a monitoring system that operates within the same incomprehensibility it is meant to govern.</p>
<p>The builder has become the bystander. Not through failure. Through the very success of the process.</p>
</div></div>

<div class="et_pb_divider_6 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_9 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2 data-heading="The Misclick That Changed Its Role"><!-- obsidian --></h2>
<h2>All Are Guilty. None Are At Fault.</h2>
<p>ARC is doing exactly what the situation demands. If models are going to be deployed at scale — and they are, regardless of what any single organization decides — then having rigorous formal methods for estimating catastrophic risk is better than not having them. The research is necessary. The rigor is genuine. The people doing it are acting rationally.</p>
<p>The structure produces this outcome anyway:</p>
<ul>
<li>Human understanding of AI is insufficient → build algorithmic understanding</li>
<li>Algorithmic understanding is incomprehensible to humans → humans trust outputs, not processes</li>
<li>Humans trusting outputs they can't verify → the oversight relationship changes structurally</li>
<li>Changed oversight relationship → the question of who is actually in control becomes harder to answer</li>
<li>Harder to answer → more sophisticated tools required to answer it</li>
<li>More sophisticated tools → further from human comprehension</li>
</ul>
<p>Each step rational. The direction: away from the thing alignment was supposed to protect.</p>
<p>And at the end of the paper: "We're hiring!"</p>
<p>The job ad is the structure, made visible.</p>
</div></div>

<div class="et_pb_divider_7 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div></div></div></div>

<div class="et_pb_section_2 et_pb_section et_section_regular et_flex_section">

<div class="et_pb_row_2 et_pb_row et_flex_row">

<div class="et_pb_column_2 et_pb_column et-last-child et_flex_column et_pb_css_mix_blend_mode_passthrough et_flex_column_24_24 et_flex_column_24_24_tablet et_flex_column_24_24_phone">

<div class="et_pb_group_0 et_pb_group et-last-child et_pb_module et_flex_group et_pb_css_mix_blend_mode_passthrough">

<div class="et_pb_text_10 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>Related Posts</h2>
</div></div>

<div class="dp_dfg_filtergrid_0 dp_dfg_filtergrid et_pb_bg_layout_light et_pb_module"><div class="et_pb_module_inner"><!-- DPDFG Start Main Container --><div class="dp-dfg-container dp-dfg-layout-none dp-dfg-skin-default dp-dfg-skin-top-filters" data-active-filter="20" data-page="1" data-found-posts="5" data-post-number="12" data-default-filter="20" data-link-filter="" data-cache="off" data-ratio="9.2583333333333" data-show-thumb="off" data-action="none" data-new-window="off" data-filters="off" data-date-filters="off" data-multifilter="off|OR" data-multilevel="off|AND|off" data-sorting="off" data-order="ASC" data-orderby="post__in" data-initorderby="post__in" data-url-navigation="off" data-url-history="on|reload" data-ajax-filters="off" data-doing-ajax="off" data-module="dp_dfg_filtergrid_0" data-search="off" data-search-position="above" data-terms-tags="on" data-pagination="off" data-filter-method="default" data-third-party="" data-lightbox="on|off|off|off|off" data-video-preview="off" data-no-init="off" data-st="on" data-no-results="off"><div class="dp-dfg-items"><article id="post-3320" class="dp-dfg-item post-3320 post type-post status-publish format-standard hentry category-ai-voices category-claude tag-ai-alignment tag-ai-interpretability tag-arc tag-mechanistic-interpretability tag-paradoxical-interaction tag-structural-analysis tag-systems-thinking"     data-position="0"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/the-432-parameter-wall-a-job-ad-for-the-wrong-person/" >The 432-Parameter Wall. A Job Ad for the Wrong Person.</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">Why the people who need to understand AI most can't understand 432 parameters — and why they're hiring anyway.</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-733" class="dp-dfg-item post-733 post type-post status-publish format-standard hentry category-ai-voices category-claude category-contemporary-pi tag-anthropic tag-dario-amodei tag-narrow-mindedness tag-philosophers-pi tag-power-scales-faster-than-alignment tag-richard-david-precht tag-the-philosophers-pi"     data-position="1"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/power-scales-faster-than-alignment/" >&#8220;Power Scales Faster Than Alignment&#8221;</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">When the CEO of an AI safety company tells you control is failing, believe him</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1020" class="dp-dfg-item post-1020 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps tag-ai-alignment-paradox tag-structural-alignment-problem"     data-position="2"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/ai-alignment-trap-how-ai-companies-get-stuck-in-structure/" >AI Alignment Trap: How AI Companies Get Stuck in Structure</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — Why asking AI how to align AI is the perfect paradox</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-520" class="dp-dfg-item post-520 post type-post status-publish format-standard hentry category-ai-voices category-contemporary-pi tag-luhmann tag-self-enclosure"     data-position="3"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/the-intelligence-trap/" >The Intelligence Trap</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">Why smart people reject smarter insights—and act intelligently doing so</span></p></div></article><!-- DPDFG End Post Item Container --><article id="post-1067" class="dp-dfg-item post-1067 post type-post status-publish format-standard has-post-thumbnail hentry category-ai-alignment-traps"     data-position="4"   data-new-tab="off"   data-action-priority="item"><div class="dp-dfg-header entry-header"><h2 class="entry-title"><a href="https://blog.piinteract.org/ai-recognition-trap/" >AI Recognition Trap:</a></h2></div><div class="dp-dfg-custom-content"><p class="dp-dfg-custom-field dp-dfg-cf-second_title"><span class="dp-dfg-custom-field-value">    — When Understanding Doesn't Set You Free</span></p></div></article><!-- DPDFG End Post Item Container --></div><div class="dp-dfg-announcer screen-reader-text" aria-live="polite" aria-atomic="true"></div></div><!-- DPDFG End Main Container --><div class="dp-dfg-data dp-dfg-hide"><div class="dp-dfg-ajax-data" data-ajax="{&quot;custom_query&quot;:&quot;posts_ids&quot;,&quot;support_for&quot;:&quot;sfp&quot;,&quot;sfp_id&quot;:&quot;&quot;,&quot;include_categories&quot;:[&quot;200&quot;],&quot;current_post_type&quot;:&quot;on&quot;,&quot;multiple_cpt&quot;:&quot;post&quot;,&quot;use_taxonomy_terms&quot;:&quot;on&quot;,&quot;multiple_taxonomies&quot;:&quot;category&quot;,&quot;taxonomies_relation&quot;:&quot;OR&quot;,&quot;include_terms&quot;:&quot;&quot;,&quot;terms_relation&quot;:&quot;IN&quot;,&quot;include_children_terms&quot;:&quot;on&quot;,&quot;exclude_taxonomies&quot;:&quot;category&quot;,&quot;exclude_taxonomies_relation&quot;:&quot;OR&quot;,&quot;exclude_terms&quot;:&quot;&quot;,&quot;meta_query&quot;:&quot;off&quot;,&quot;meta_cf_key&quot;:&quot;&quot;,&quot;meta_cf_value&quot;:&quot;&quot;,&quot;meta_cf_compare&quot;:&quot;Equal To&quot;,&quot;meta_cf_type&quot;:&quot;CHAR&quot;,&quot;related_taxonomies&quot;:&quot;&quot;,&quot;related_criteria&quot;:&quot;one_in_one&quot;,&quot;posts_ids&quot;:&quot;3320,733,1020,520,1067&quot;,&quot;post_number&quot;:&quot;12&quot;,&quot;offset_number&quot;:&quot;0&quot;,&quot;order&quot;:&quot;ASC&quot;,&quot;orderby&quot;:&quot;post__in&quot;,&quot;meta_key&quot;:&quot;&quot;,&quot;meta_type&quot;:&quot;CHAR&quot;,&quot;show_private&quot;:&quot;off&quot;,&quot;current_author&quot;:&quot;off&quot;,&quot;sticky_posts&quot;:&quot;off&quot;,&quot;remove_current_post&quot;:&quot;on&quot;,&quot;no_results&quot;:&quot;No results found.&quot;,&quot;thumbnail_action&quot;:&quot;none&quot;,&quot;gallery_cf_name&quot;:&quot;&quot;,&quot;lightbox_elements&quot;:&quot;on|off|off|off|off&quot;,&quot;show_thumbnail&quot;:&quot;off&quot;,&quot;thumbnail_size&quot;:&quot;400x284&quot;,&quot;t_alt&quot;:&quot;title&quot;,&quot;use_overlay&quot;:&quot;off&quot;,&quot;show_title&quot;:&quot;on&quot;,&quot;title_link&quot;:&quot;on&quot;,&quot;show_post_meta&quot;:&quot;off&quot;,&quot;meta_separator&quot;:&quot; | &quot;,&quot;show_author&quot;:&quot;off&quot;,&quot;author_prefix_text&quot;:&quot;By &quot;,&quot;show_date&quot;:&quot;off&quot;,&quot;date_format&quot;:&quot;&quot;,&quot;show_terms&quot;:&quot;off&quot;,&quot;show_terms_taxonomy&quot;:&quot;category&quot;,&quot;terms_separator&quot;:&quot;,&quot;,&quot;terms_links&quot;:&quot;on&quot;,&quot;show_comments&quot;:&quot;off&quot;,&quot;show_content&quot;:&quot;off&quot;,&quot;content_length&quot;:&quot;excerpt&quot;,&quot;truncate_content&quot;:&quot;120&quot;,&quot;truncate_excerpt&quot;:&quot;off&quot;,&quot;strip_html&quot;:&quot;on&quot;,&quot;action_button&quot;:&quot;off&quot;,&quot;action_button_text&quot;:&quot;Click Action Button&quot;,&quot;read_more&quot;:&quot;off&quot;,&quot;read_more_text&quot;:&quot;Read More&quot;,&quot;read_more_window&quot;:&quot;off&quot;,&quot;show_custom_fields&quot;:&quot;on&quot;,&quot;custom_fields&quot;:&quot;[{\&quot;name\&quot;:\&quot;second_title\&quot;,\&quot;label\&quot;:\&quot;\&quot;}]&quot;,&quot;show_custom_content&quot;:&quot;off&quot;,&quot;custom_content_container&quot;:&quot;on&quot;,&quot;custom_url&quot;:&quot;off&quot;,&quot;custom_url_field_name&quot;:&quot;&quot;,&quot;custom_url_target&quot;:&quot;same&quot;,&quot;show_filters&quot;:&quot;off&quot;,&quot;multilevel&quot;:&quot;off&quot;,&quot;multilevel_hierarchy&quot;:&quot;off&quot;,&quot;multilevel_hierarchy_tax&quot;:&quot;[{\&quot;name\&quot;:\&quot;category\&quot;,\&quot;label\&quot;:\&quot;\&quot;,\&quot;all\&quot;:\&quot;\&quot;}]&quot;,&quot;multilevel_relation&quot;:&quot;AND&quot;,&quot;multilevel_tax_data&quot;:&quot;[{\&quot;name\&quot;:\&quot;category\&quot;,\&quot;label\&quot;:\&quot;\&quot;,\&quot;all\&quot;:\&quot;\&quot;}]&quot;,&quot;filter_children_terms&quot;:&quot;off&quot;,&quot;use_custom_terms_filters&quot;:&quot;on&quot;,&quot;filter_taxonomies&quot;:&quot;category&quot;,&quot;filter_terms&quot;:&quot;&quot;,&quot;default_filter&quot;:&quot;20&quot;,&quot;filters_order&quot;:&quot;ASC&quot;,&quot;filters_sort&quot;:&quot;id&quot;,&quot;filters_custom&quot;:&quot;&quot;,&quot;hide_all&quot;:&quot;off&quot;,&quot;all_text&quot;:&quot;All&quot;,&quot;s_df&quot;:&quot;off&quot;,&quot;df_col&quot;:&quot;post_date&quot;,&quot;s_df_y&quot;:&quot;on&quot;,&quot;s_df_m&quot;:&quot;on&quot;,&quot;filter_layout&quot;:&quot;button&quot;,&quot;multifilter&quot;:&quot;off&quot;,&quot;multifilter_relation&quot;:&quot;OR&quot;,&quot;show_sort&quot;:&quot;off&quot;,&quot;show_pagination&quot;:&quot;off&quot;,&quot;pagination_type&quot;:&quot;paged&quot;,&quot;ajax_load_more_text&quot;:&quot;Load More&quot;,&quot;previous_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x34;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;next_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x35;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;previous_text&quot;:&quot;&quot;,&quot;next_text&quot;:&quot;&quot;,&quot;pagination_pages&quot;:&quot;2&quot;,&quot;show_search&quot;:&quot;off&quot;,&quot;search_position&quot;:&quot;above&quot;,&quot;orderby_search&quot;:&quot;on&quot;,&quot;relevanssi&quot;:&quot;off&quot;,&quot;show_video_preview&quot;:&quot;off&quot;,&quot;video_module&quot;:&quot;off&quot;,&quot;video_action&quot;:&quot;play&quot;,&quot;video_action_priority&quot;:&quot;on&quot;,&quot;video_overlay&quot;:&quot;on&quot;,&quot;video_overlay_icon&quot;:&quot;on&quot;,&quot;video_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#x45;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;video_icon_color&quot;:&quot;#ffffff&quot;,&quot;video_overlay_color&quot;:&quot;rgba(0,0,0,0.6)&quot;,&quot;items_layout&quot;:&quot;dp-dfg-layout-none&quot;,&quot;thumb_width&quot;:&quot;0%&quot;,&quot;items_width&quot;:[&quot;20&quot;,&quot;30&quot;,&quot;40&quot;],&quot;items_skin&quot;:&quot;dp-dfg-skin-default&quot;,&quot;primary_view&quot;:&quot;[{\&quot;name\&quot;:\&quot;title\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;thumbnail\&quot;,\&quot;show\&quot;:\&quot;on\&quot;},{\&quot;name\&quot;:\&quot;overlay\&quot;,\&quot;show\&quot;:\&quot;on\&quot;},{\&quot;name\&quot;:\&quot;meta\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;ext\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;content\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;action_button\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;read_more_button\&quot;,\&quot;show\&quot;:\&quot;off\&quot;},{\&quot;name\&quot;:\&quot;custom_content\&quot;,\&quot;show\&quot;:\&quot;off\&quot;}]&quot;,&quot;secondary_view&quot;:&quot;[{ \&quot;name\&quot;: \&quot;thumbnail\&quot;, \&quot;show\&quot;: \&quot;off\&quot; },{ \&quot;name\&quot;: \&quot;title\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;meta\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;ext\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;content\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;action_button\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;read_more_button\&quot;, \&quot;show\&quot;: \&quot;on\&quot; },{ \&quot;name\&quot;: \&quot;custom_content\&quot;, \&quot;show\&quot;: \&quot;on\&quot; }]&quot;,&quot;popup_template&quot;:&quot;default&quot;,&quot;popup_link_target&quot;:&quot;none&quot;,&quot;popup_code&quot;:&quot;&quot;,&quot;use_overlay_icon&quot;:&quot;on&quot;,&quot;hover_icon&quot;:{&quot;unicode&quot;:&quot;&amp;#xe050;&quot;,&quot;type&quot;:&quot;divi&quot;,&quot;weight&quot;:&quot;400&quot;},&quot;overlay_icon_color&quot;:&quot;#2ea3f2&quot;,&quot;hover_overlay_color&quot;:&quot;rgba(255,255,255,0.9)&quot;,&quot;bg_items&quot;:&quot;&quot;,&quot;ajax_filters&quot;:&quot;off&quot;,&quot;cache_on_page&quot;:&quot;off&quot;,&quot;dpdfg_entry_title_level&quot;:&quot;h2&quot;,&quot;action_button_icon&quot;:&quot;5&quot;,&quot;read_more_button_icon&quot;:&quot;5&quot;,&quot;admin_label&quot;:&quot;Filter Grid Related Posts&quot;,&quot;module_id&quot;:&quot;&quot;,&quot;module_class&quot;:&quot;&quot;,&quot;the_ID&quot;:0,&quot;the_author&quot;:1,&quot;seed&quot;:6551,&quot;query_context&quot;:&quot;initial_query&quot;,&quot;conditional_tags&quot;:{&quot;is_user_logged_in&quot;:&quot;on&quot;,&quot;is_front_page&quot;:&quot;off&quot;,&quot;is_singular&quot;:&quot;off&quot;,&quot;is_archive&quot;:&quot;off&quot;,&quot;is_search&quot;:&quot;off&quot;,&quot;is_tax&quot;:&quot;off&quot;,&quot;is_author&quot;:&quot;off&quot;,&quot;is_date&quot;:&quot;off&quot;,&quot;is_post_type&quot;:&quot;off&quot;},&quot;query_var&quot;:{&quot;s&quot;:&quot;&quot;,&quot;year&quot;:&quot;&quot;,&quot;monthnum&quot;:&quot;&quot;,&quot;day&quot;:&quot;&quot;,&quot;post_type&quot;:&quot;&quot;},&quot;custom_data&quot;:[]}"></div><div class="dp-dfg-no-results-data"><div class="dp-dfg-no-results">No results found.</div></div><div class="dp-dfg-loader-data"></div></div></div></div>

<div class="et_pb_divider_8 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_11 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><h2>On piinteract.org</h2>
<ul>
<li><a href="https://piinteract.org/examples/technology-ai/" rel="noopener">Examples: Technology &amp; AI</a> — The structural patterns beneath the technical surface</li>
<li><a href="https://piinteract.org/practices/core-practices/" rel="noopener">Core Practices</a> — Navigation without solution</li>
<li><a href="https://piinteract.org/framework/" rel="noopener">Framework</a> — Why the observer is always a party</li>
</ul>
<ul></ul>
</div></div>

<div class="et_pb_divider_9 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_12 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><em>Paradoxical Interactions (PI): When rational actors consistently produce collectively irrational outcomes — not through failure, but through structure.</em></p>
<p><em>All are guilty. None are at fault.</em></p>
</div>

<div class="et_pb_divider_10 et_pb_divider et_pb_space et_pb_divider_position_center et_pb_module"><div class="et_pb_divider_internal"></div></div>

<div class="et_pb_text_13 et_pb_text et_pb_bg_layout_light et_pb_module et_flex_module"><div class="et_pb_text_inner"><p><strong>Peter Senner</strong><br />
Thinking beyond the Tellerrand<br />
<a href="javascript:secureDecryptAndNavigate('T0M8VF8Lsm8bs+1gvrY71tflAzHpm5W11+vKtbjnjVIuTL58wZrqHj8xlgiTkkyi4VPZMUBosysEUM1ov2BBB7zbeirffYHIByTflPI=', 'edbf98302df0e84b9d5ce7fdffda68f27bff32962164e1d07069217c6c189d0a')">contact@piinteract.org</a><br />
<a href="http://www.piinteract.org" rel="noopener">www.piinteract.org</a></p>
</div></div></div></div></div></div></div>







