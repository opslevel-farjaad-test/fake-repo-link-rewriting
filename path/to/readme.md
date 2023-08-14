* fake_org = johntrandall
* fake_projct = fake-repo-link-rewriting



# EXCLUDED FROM FETCH

* content_line: derp derp,
    * derp serp,

* content_line: "I am not markdown link.",
    * "I am not markdown link.",

# EXCLUDED - Markdown
* content_line: \!\[different domain different path with protocol no filename](http://google.com) excluded from fetch,
    * ![different domain different path with protocol no filename](http://google.com) excluded from fetch,

* content_line: \!\[different domain different path with protocol with filename](http://google.com/excluded from fetch.jpg) excluded from fetch,
    * ![different domain different path with protocol with filename](http://google.com/excluded from fetch.jpg) excluded from fetch,

* content_line: \!\[different domain same path with protocol no filename](http://google.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,
    * ![different domain same path with protocol no filename](http://google.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,

* content_line: \!\[different domain same path with protocol with filename](http://google.com/johntrandall/fake-repo-link-rewriting/excluded from fetch.jpg) excluded from fetch,
    * ![different domain same path with protocol with filename](http://google.com/johntrandall/fake-repo-link-rewriting/excluded from fetch.jpg) excluded from fetch,

* content_line: \!\[same domain different path with protocol no filename](http://github.com) excluded from fetch,
    * ![same domain different path with protocol no filename](http://github.com) excluded from fetch,

* content_line: \!\[same domain different path with protocol with filename](http://github.com/excluded from fetch.jpg) excluded from fetch,
    * ![same domain different path with protocol with filename](http://github.com/excluded from fetch.jpg) excluded from fetch,

* content_line: \!\[in repo with protocol no filename](https://github.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,
    * ![in repo with protocol no filename](https://github.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,

* content_line: \!\[in repo with weird protocol no filename](file://github.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,
    * ![in repo with weird protocol no filename](file://github.com/johntrandall/fake-repo-link-rewriting) excluded from fetch,

* content_line: \!\[relative to containing markdown - direct wrong extension bitmap](excluded from fetch.bmp) excluded from fetch,
    * ![relative to containing markdown - direct wrong extension bitmap](excluded from fetch.bmp) excluded from fetch,

* content_line: \!\[relative to containing markdown - direct wrong extension markdown](excluded from fetch.md) excluded from fetch,
    * ![relative to containing markdown - direct wrong extension markdown](excluded from fetch.md) excluded from fetch,

* content_line: \!\[relative to containing markdown - direct no bang](excluded from fetch.jpg) excluded from fetch",
    * "[relative to containing markdown - direct no bang](excluded from fetch.jpg) excluded from fetch",

* content_line: \!\[relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) excluded from fetch,
    * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) excluded from fetch,

* content_line: \!\[relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) excluded from fetch",
    * '![relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) excluded from fetch",



# EXCLUDED - HTML
* content_line: \<img src="http://google.com" alt="tag different domain different path with protocol"> excluded from fetch,
    * <img src="http://google.com" alt="tag different domain different path with protocol"> excluded from fetch,

* content_line: \<img src="http://google.com/excluded from fetch.jpg" alt="tag different domain different path with protocol with filename"> excluded from fetch,
    * <img src="http://google.com/excluded from fetch.jpg" alt="tag different domain different path with protocol with filename"> excluded from fetch,

* content_line: \<img src="http://google.com/johntrandall/fake-repo-link-rewriting" alt="tag different domain same path with protocol"> excluded from fetch,
    * <img src="http://google.com/johntrandall/fake-repo-link-rewriting" alt="tag different domain same path with protocol"> excluded from fetch,

* content_line: \<img src="http://google.com/johntrandall/fake-repo-link-rewriting/excluded from fetch.jpg" alt="tag different domain same path with protocol with filename"> excluded from fetch,
    * <img src="http://google.com/johntrandall/fake-repo-link-rewriting/excluded from fetch.jpg" alt="tag different domain same path with protocol with filename"> excluded from fetch,

* content_line: \<img src="http://github.com" alt="tag same domain different path with protocol no filename"> excluded from fetch,
    * <img src="http://github.com" alt="tag same domain different path with protocol no filename"> excluded from fetch,

* content_line: \<img src="http://github.com/excluded from fetch.jpg" alt="tag same domain different path with protocol with filename"> excluded from fetch,
    * <img src="http://github.com/excluded from fetch.jpg" alt="tag same domain different path with protocol with filename"> excluded from fetch,

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with protocol no filename"> excluded from fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with protocol no filename"> excluded from fetch,
  
* content_line: \<img src="file://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with weird protocol no filename"> excluded from fetch,
    * <img src="file://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with weird protocol no filename"> excluded from fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",
    * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",

* content_line: \<img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",
    * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",

* content_line: \<img src="excluded from fetch.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> excluded from fetch,
    * <img src="excluded from fetch.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> excluded from fetch,

* content_line: \<img src="excluded from fetch.md" alt="tag relative to containing markdown - direct wrong extension markdown"> excluded from fetch,
    * <img src="excluded from fetch.md" alt="tag relative to containing markdown - direct wrong extension markdown"> excluded from fetch,
  
  
  
  
# INCLUDED IN FETCH

# INCLUDED Markdown

## FULL PROTOCOL
* content_line: \!\[in repo with protocol with filename]\(https://github.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) included in fetch,
    * ![in repo with protocol with filename](https://github.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) included in fetch,

* content_line: \!\[in repo with weird protocol with filename]\(file://github.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) included in fetch,
    * ![in repo with weird protocol with filename](file://github.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) included in fetch,

* content_line: \!\[in repo with protocol with filename subfoldered]\(https://github.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) included in fetch,
    * ![in repo with protocol with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) included in fetch,

* content_line: \!\[in repo with protocol with branch with filename]\(https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) included in fetch,
    * ![in repo with protocol with branch with filename](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) included in fetch,

* content_line: \!\[in repo with protocol with branch with filename subfoldered]\(https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) included in fetch,
    * ![in repo with protocol with branch with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) included in fetch,

* content_line: \!\[in repo with protocol with branch with filename subfoldered with anchor and query]\(https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) included in fetch,
    * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) included in fetch,

## RELATIVE 
* content_line: \!\[relative to repo root]\(/relative_to_repo_root.jpg) included in fetch,
    * ![relative to repo root](/relative_to_repo_root.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - direct sibling]\(relative_to_markdown_direct_sibling.jpg) included in fetch,
    * ![relative to containing markdown - direct sibling](relative_to_markdown_direct_sibling.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - direct sibling subfoldered]\(subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) included in fetch,
    * ![relative to containing markdown - direct sibling subfoldered](subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) included in fetch,

* content_line: !\[relative to containing markdown - cousin subfoldered \(down one up one)]\(../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED,
    * ![relative to containing markdown - cousin subfoldered (down one up one)](../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED,

* content_line: \!\[relative to containing markdown - direct sibling subfoldered with confusing folder name]\(github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) included in fetch,
    * ![relative to containing markdown - direct sibling subfoldered with confusing folder name](github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - dot slash ]\(./relative_to_markdown_dot_slash.jpg) included in fetch,
    * ![relative to containing markdown - dot slash ](./relative_to_markdown_dot_slash.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - dot slash subfoldered]\(./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) included in fetch,
    * ![relative to containing markdown - dot slash subfoldered](./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - dot slash subfoldered with confusing folder name]\(./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) included in fetch,
    * ![relative to containing markdown - dot slash subfoldered with confusing folder name](./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - in repo up one]\(../relative_to_containing_markdown_up_one.jpg) included in fetch,
    * ![relative to containing markdown - in repo up one](../relative_to_containing_markdown_up_one.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - in repo up two]\(../../relative_to_containing_markdown_up_two.jpg) included in fetch,
    * ![relative to containing markdown - in repo up two](../../relative_to_containing_markdown_up_two.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - up past root]\(../../../../relative_to_containing_markdown_up_past_root.jpg) included in fetch,
    * ![relative to containing markdown - up past root](../../../../relative_to_containing_markdown_up_past_root.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - direct duplicate]\(relative_to_markdown_direct_duplicate.jpg) included in fetch,
    * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) included in fetch,

* content_line: \!\[relative to containing markdown - direct with video]\(relative_to_markdown_direct_video.mp4) included in fetch,
    * ![relative to containing markdown - direct with video](relative_to_markdown_direct_video.mp4) included in fetch,

* content_line: \!\[relative to containing markdown - direct with anchor]\(relative_to_markdown_direct_anchor.jpg#anchor) included in fetch,
    * ![relative to containing markdown - direct with anchor](relative_to_markdown_direct_anchor.jpg#anchor) included in fetch,

* content_line: \!\[relative to containing markdown - direct with query parmas]\(relative_to_markdown_direct_query.jpg?query) included in fetch,
    * ![relative to containing markdown - direct with query parmas](relative_to_markdown_direct_query.jpg?query) included in fetch,

* content_line: \!\[relative to containing markdown - direct with query and anchor]\(relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) included in fetch,
    * ![relative to containing markdown - direct with query and anchor](relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) included in fetch,

* content_line: \!\[relative to containing markdown - direct with anchor and query]\(relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) included in fetch,
    * ![relative to containing markdown - direct with anchor and query](relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) included in fetch,


# INCLUDED HTML

## FULL PROTOCOL - from Main
* THESE DO NOT WORK IN GITHUB

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> included in fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> included in fetch,

* content_line: \<img src="file://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> included in fetch,
    * <img src="file://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> included in fetch,

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> included in fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> included in fetch,

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> included in fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> included in fetch,

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> included in fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> included in fetch,

* content_line: \<img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> included in fetch,
    * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> included in fetch,

  
## RELATIVE
* content_line: \<img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> included in fetch,
    * <img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> included in fetch,

* content_line: \<img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> included in fetch,
    * <img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> included in fetch,

* content_line: \<img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> included in fetch,
    * <img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> included in fetch,

* content_line: \<img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> included in fetch,
    * <img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> included in fetch,

* content_line: \<img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> included in fetch,
    * <img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> included in fetch,

* content_line: \<img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> included in fetch,
    * <img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> included in fetch,

* content_line: \<img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> included in fetch,
    * <img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> included in fetch,

* content_line: \<img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> included in fetch,
    * <img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> included in fetch,

* content_line: \<img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> included in fetch,
    * <img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> included in fetch,

* content_line: \<img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> included in fetch,
    * <img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> included in fetch,

* content_line: \<img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> included in fetch,
    * <img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> included in fetch,
