fake_org = johntrandall
fake_projct = fake-repo-link-rewriting

* content_line: derp derp,
  * derp serp,

* content_line: "I am not markdown link.",
  * "I am not markdown link.",

* content_line: different domain different path with protocol no filename](http://google.com) EXCLUDED FROM FETCH,
  * ![different domain different path with protocol no filename](http://google.com) EXCLUDED FROM FETCH,

* content_line: different domain different path with protocol with filename](http://google.com/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,
  * ![different domain different path with protocol with filename](http://google.com/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,

* content_line: different domain same path with protocol no filename](http://google.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,
  * ![different domain same path with protocol no filename](http://google.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,

* content_line: different domain same path with protocol with filename](http://google.com/johntrandall/fake-repo-link-rewriting/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,
  * ![different domain same path with protocol with filename](http://google.com/johntrandall/fake-repo-link-rewriting/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,

* content_line: same domain different path with protocol no filename](http://github.com) EXCLUDED FROM FETCH,
  * ![same domain different path with protocol no filename](http://github.com) EXCLUDED FROM FETCH,

* content_line: same domain different path with protocol with filename](http://github.com/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,
  * ![same domain different path with protocol with filename](http://github.com/EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH,

* content_line: in repo with protocol no filename](https://github.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,
  * ![in repo with protocol no filename](https://github.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,

* content_line: in repo with protocol with filename](https://github.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename](https://github.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with protocol with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with protocol with filename](https://bitbucket.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename](https://bitbucket.com/johntrandall/fake-repo-link-rewriting/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ject/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ject/in_repo_with_protocol_with_filename.jpg) INCLUDED IN FETCH,

* content_line: in repo with weird protocol no filename](file://github.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,
  * ![in repo with weird protocol no filename](file://github.com/johntrandall/fake-repo-link-rewriting) EXCLUDED FROM FETCH,

* content_line: in repo with weird protocol with filename](file://github.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with weird protocol with filename](file://github.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with weird protocol with filename](file://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with weird protocol with filename](file://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with weird protocol with filename](file://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with weird protocol with filename](file://gitlab.com/johntrandall/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
* content_line__azure: ![in repo with weird protocoldev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with weird protocoldev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/fake-repo-link-rewriting/in_repo_weird_protocol_with_filename.jpg) INCLUDED IN FETCH,

* content_line: in repo with protocol with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with protocol with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with protocol with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/org/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/org/fake-repo-link-rewriting/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED IN FETCH,

* content_line: in repo with protocol with branch with filename](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with protocol with branch with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with protocol with branch with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/e_org/fake-repo-link-rewriting/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/e_org/fake-repo-link-rewriting/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED IN FETCH,

* content_line: in repo with protocol with branch with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/tlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/tlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED IN FETCH,

* content_line: in repo with protocol with branch with filename subfoldered with anchor and query](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
* content_line__gitlab: ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
* content_line__bitbucket: ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ and query](https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED IN FETCH,

* content_line: relative to repo root](/relative_to_repo_root.jpg) INCLUDED IN FETCH,
  * ![relative to repo root](/relative_to_repo_root.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct sibling](relative_to_markdown_direct_sibling.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct sibling](relative_to_markdown_direct_sibling.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct sibling subfoldered](subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct sibling subfoldered](subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - cousin subfoldered (down one up one)](../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - cousin subfoldered (down one up one)](../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct sibling subfoldered with confusing folder name](github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct sibling subfoldered with confusing folder name](github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - dot slash ](./relative_to_markdown_dot_slash.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - dot slash ](./relative_to_markdown_dot_slash.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - dot slash subfoldered](./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - dot slash subfoldered](./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - dot slash subfoldered with confusing folder name](./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - dot slash subfoldered with confusing folder name](./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - in repo up one](../relative_to_containing_markdown_up_one.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - in repo up one](../relative_to_containing_markdown_up_one.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - in repo up two](../../relative_to_containing_markdown_up_two.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - in repo up two](../../relative_to_containing_markdown_up_two.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - up past root](../../../../relative_to_containing_markdown_up_past_root.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - up past root](../../../../relative_to_containing_markdown_up_past_root.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct wrong extension bitmap](EXCLUDED FROM FETCH.bmp) EXCLUDED FROM FETCH,
  * ![relative to containing markdown - direct wrong extension bitmap](EXCLUDED FROM FETCH.bmp) EXCLUDED FROM FETCH,

* content_line: relative to containing markdown - direct wrong extension markdown](EXCLUDED FROM FETCH.md) EXCLUDED FROM FETCH,
  * ![relative to containing markdown - direct wrong extension markdown](EXCLUDED FROM FETCH.md) EXCLUDED FROM FETCH,

* content_line: "[relative to containing markdown - direct no bang](EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH",
  * "[relative to containing markdown - direct no bang](EXCLUDED FROM FETCH.jpg) EXCLUDED FROM FETCH",

* content_line: relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) EXCLUDED,
  * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) EXCLUDED,

* content_line: '![relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) EXCLUDED",
  * '![relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) EXCLUDED",

* content_line: relative to containing markdown - direct with video](relative_to_markdown_direct_video.mp4) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct with video](relative_to_markdown_direct_video.mp4) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct with anchor](relative_to_markdown_direct_anchor.jpg#anchor) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct with anchor](relative_to_markdown_direct_anchor.jpg#anchor) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct with query parmas](relative_to_markdown_direct_query.jpg?query) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct with query parmas](relative_to_markdown_direct_query.jpg?query) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct with query and anchor](relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct with query and anchor](relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) INCLUDED IN FETCH,

* content_line: relative to containing markdown - direct with anchor and query](relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) INCLUDED IN FETCH,
  * ![relative to containing markdown - direct with anchor and query](relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) INCLUDED IN FETCH,

* content_line: "I am not an image tag.",
  * "I am not an image tag.",

* content_line: <img src="http://google.com" alt="tag different domain different path with protocol"> EXCLUDED FROM FETCH,
  * <img src="http://google.com" alt="tag different domain different path with protocol"> EXCLUDED FROM FETCH,

* content_line: <img src="http://google.com/EXCLUDED FROM FETCH.jpg" alt="tag different domain different path with protocol with filename"> EXCLUDED FROM FETCH,
  * <img src="http://google.com/EXCLUDED FROM FETCH.jpg" alt="tag different domain different path with protocol with filename"> EXCLUDED FROM FETCH,

* content_line: <img src="http://google.com/johntrandall/fake-repo-link-rewriting" alt="tag different domain same path with protocol"> EXCLUDED FROM FETCH,
  * <img src="http://google.com/johntrandall/fake-repo-link-rewriting" alt="tag different domain same path with protocol"> EXCLUDED FROM FETCH,

* content_line: <img src="http://google.com/johntrandall/fake-repo-link-rewriting/EXCLUDED FROM FETCH.jpg" alt="tag different domain same path with protocol with filename"> EXCLUDED FROM FETCH,
  * <img src="http://google.com/johntrandall/fake-repo-link-rewriting/EXCLUDED FROM FETCH.jpg" alt="tag different domain same path with protocol with filename"> EXCLUDED FROM FETCH,

* content_line: <img src="http://github.com" alt="tag same domain different path with protocol no filename"> EXCLUDED FROM FETCH,
  * <img src="http://github.com" alt="tag same domain different path with protocol no filename"> EXCLUDED FROM FETCH,

* content_line: <img src="http://github.com/EXCLUDED FROM FETCH.jpg" alt="tag same domain different path with protocol with filename"> EXCLUDED FROM FETCH,
  * <img src="http://github.com/EXCLUDED FROM FETCH.jpg" alt="tag same domain different path with protocol with filename"> EXCLUDED FROM FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with protocol no filename"> EXCLUDED FROM FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with protocol no filename"> EXCLUDED FROM FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED IN FETCH,

* content_line: <img src="file://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with weird protocol no filename"> EXCLUDED FROM FETCH,
  * <img src="file://github.com/johntrandall/fake-repo-link-rewriting" alt="tag in repo with weird protocol no filename"> EXCLUDED FROM FETCH,

* content_line: <img src="file://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
  * <img src="file://github.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="file://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
  * <img src="file://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="file://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
  * <img src="file://gitlab.com/johntrandall/fake-repo-link-rewriting/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
* content_line__azure: <img src="file://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,
  * <img src="file://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED IN FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED IN FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED IN FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED IN FETCH,

* content_line: <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
  * <img src="https://github.com/johntrandall/fake-repo-link-rewriting/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
* content_line__gitlab: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
* content_line__bitbucket: <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
  * <img src="https://gitlab.com/johntrandall/fake-repo-link-rewriting/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED IN FETCH,

* content_line: <img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> INCLUDED IN FETCH,
  * <img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> INCLUDED IN FETCH,

* content_line: <img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> INCLUDED IN FETCH,
  * <img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> INCLUDED IN FETCH,

* content_line: <img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> INCLUDED IN FETCH,
  * <img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> INCLUDED IN FETCH,

* content_line: <img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> INCLUDED IN FETCH,
  * <img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> INCLUDED IN FETCH,

* content_line: <img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> INCLUDED IN FETCH,
  * <img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> INCLUDED IN FETCH,

* content_line: <img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> INCLUDED IN FETCH,
  * <img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> INCLUDED IN FETCH,

* content_line: <img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> INCLUDED IN FETCH,
  * <img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> INCLUDED IN FETCH,

* content_line: <img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> INCLUDED IN FETCH,
  * <img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> INCLUDED IN FETCH,

* content_line: <img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> INCLUDED IN FETCH,
  * <img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> INCLUDED IN FETCH,

* content_line: <img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> INCLUDED IN FETCH,
  * <img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",

* content_line: <img src="EXCLUDED FROM FETCH.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> EXCLUDED FROM FETCH,
  * <img src="EXCLUDED FROM FETCH.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> EXCLUDED FROM FETCH,

* content_line: <img src="EXCLUDED FROM FETCH.md" alt="tag relative to containing markdown - direct wrong extension markdown"> EXCLUDED FROM FETCH,
  * <img src="EXCLUDED FROM FETCH.md" alt="tag relative to containing markdown - direct wrong extension markdown"> EXCLUDED FROM FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> INCLUDED IN FETCH,

* content_line: <img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> INCLUDED IN FETCH,
  * <img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> INCLUDED IN FETCH,
