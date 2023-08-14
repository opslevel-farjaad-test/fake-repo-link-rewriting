
* content_line: derp derp,
  * derp serp,

* content_line: "I am not markdown link.",
  * "I am not markdown link.",

* content_line: different domain different path with protocol no filename](http://google.com) excluded,
  * ![different domain different path with protocol no filename](http://google.com) excluded,

* content_line: different domain different path with protocol with filename](http://google.com/excluded.jpg) excluded,
  * ![different domain different path with protocol with filename](http://google.com/excluded.jpg) excluded,

* content_line: different domain same path with protocol no filename](http://google.com/fake_org/fake_project) excluded,
  * ![different domain same path with protocol no filename](http://google.com/fake_org/fake_project) excluded,

* content_line: different domain same path with protocol with filename](http://google.com/fake_org/fake_project/excluded.jpg) excluded,
  * ![different domain same path with protocol with filename](http://google.com/fake_org/fake_project/excluded.jpg) excluded,

* content_line: same domain different path with protocol no filename](http://github.com) excluded,
  * ![same domain different path with protocol no filename](http://github.com) excluded,

* content_line: same domain different path with protocol with filename](http://github.com/excluded.jpg) excluded,
  * ![same domain different path with protocol with filename](http://github.com/excluded.jpg) excluded,

* content_line: in repo with protocol no filename](https://github.com/fake_org/fake_project) excluded,
  * ![in repo with protocol no filename](https://github.com/fake_org/fake_project) excluded,

* content_line: in repo with protocol with filename](https://github.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with filename](https://github.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
* content_line__gitlab: ![in repo with protocol with filename](https://gitlab.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with filename](https://gitlab.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
* content_line__bitbucket: ![in repo with protocol with filename](https://bitbucket.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with filename](https://bitbucket.com/fake_org/fake_project/in_repo_with_protocol_with_filename.jpg) INCLUDED,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ject/in_repo_with_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ject/in_repo_with_protocol_with_filename.jpg) INCLUDED,

* content_line: in repo with weird protocol no filename](file://github.com/fake_org/fake_project) excluded,
  * ![in repo with weird protocol no filename](file://github.com/fake_org/fake_project) excluded,

* content_line: in repo with weird protocol with filename](file://github.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with weird protocol with filename](file://github.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
* content_line__gitlab: ![in repo with weird protocol with filename](file://gitlab.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with weird protocol with filename](file://gitlab.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
* content_line__bitbucket: ![in repo with weird protocol with filename](file://gitlab.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with weird protocol with filename](file://gitlab.com/fake_org/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
* content_line__azure: ![in repo with weird protocoldev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,
  * ![in repo with weird protocoldev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/fake_project/in_repo_weird_protocol_with_filename.jpg) INCLUDED,

* content_line: in repo with protocol with filename subfoldered](https://github.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with filename subfoldered](https://github.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
* content_line__gitlab: ![in repo with protocol with filename subfoldered](https://gitlab.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with filename subfoldered](https://gitlab.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
* content_line__bitbucket: ![in repo with protocol with filename subfoldered](https://gitlab.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with filename subfoldered](https://gitlab.com/fake_org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/org/fake_project/path/to/in_repo_with_protocol_with_filename_subfoldered.jpg) INCLUDED,

* content_line: in repo with protocol with branch with filename](https://github.com/fake_org/fake_project/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename](https://github.com/fake_org/fake_project/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
* content_line__gitlab: ![in repo with protocol with branch with filename](https://gitlab.com/fake_org/fake_project/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename](https://gitlab.com/fake_org/fake_project/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
* content_line__bitbucket: ![in repo with protocol with branch with filename](https://gitlab.com/fake_org/fake_project/src/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename](https://gitlab.com/fake_org/fake_project/src/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/e_org/fake_project/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/e_org/fake_project/-/blob/main/in_repo_with_protocol_with_branch_with_filename.jpg) INCLUDED,

* content_line: in repo with protocol with branch with filename subfoldered](https://github.com/fake_org/fake_project/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered](https://github.com/fake_org/fake_project/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
* content_line__gitlab: ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
* content_line__bitbucket: ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/fake_org/fake_project/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered](https://gitlab.com/fake_org/fake_project/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/tlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/tlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg) INCLUDED,

* content_line: in repo with protocol with branch with filename subfoldered with anchor and query](https://github.com/fake_org/fake_project/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://github.com/fake_org/fake_project/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
* content_line__gitlab: ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
* content_line__bitbucket: ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/fake_org/fake_project/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
  * ![in repo with protocol with branch with filename subfoldered with anchor and query](https://gitlab.com/fake_org/fake_project/src/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
* content_line__azure: ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ and query](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,
  * ![in repo with protocol withdev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/ and query](https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X) INCLUDED,

* content_line: relative to repo root](/relative_to_repo_root.jpg) INCLUDED,
  * ![relative to repo root](/relative_to_repo_root.jpg) INCLUDED,

* content_line: relative to containing markdown - direct sibling](relative_to_markdown_direct_sibling.jpg) INCLUDED,
  * ![relative to containing markdown - direct sibling](relative_to_markdown_direct_sibling.jpg) INCLUDED,

* content_line: relative to containing markdown - direct sibling subfoldered](subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) INCLUDED,
  * ![relative to containing markdown - direct sibling subfoldered](subfolder/relative_to_markdown_direct_sibling_subfoldered.jpg) INCLUDED,

* content_line: relative to containing markdown - cousin subfoldered (down one up one)](../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED,
  * ![relative to containing markdown - cousin subfoldered (down one up one)](../subfolder/relative_to_markdown_cousin_subfoldered.jpg) INCLUDED,

* content_line: relative to containing markdown - direct sibling subfoldered with confusing folder name](github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) INCLUDED,
  * ![relative to containing markdown - direct sibling subfoldered with confusing folder name](github.com/relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg) INCLUDED,

* content_line: relative to containing markdown - dot slash ](./relative_to_markdown_dot_slash.jpg) INCLUDED,
  * ![relative to containing markdown - dot slash ](./relative_to_markdown_dot_slash.jpg) INCLUDED,

* content_line: relative to containing markdown - dot slash subfoldered](./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) INCLUDED,
  * ![relative to containing markdown - dot slash subfoldered](./subfolder/relative_to_markdown_dot_slash_subfoldered.jpg) INCLUDED,

* content_line: relative to containing markdown - dot slash subfoldered with confusing folder name](./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) INCLUDED,
  * ![relative to containing markdown - dot slash subfoldered with confusing folder name](./github.com/relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg) INCLUDED,

* content_line: relative to containing markdown - in repo up one](../relative_to_containing_markdown_up_one.jpg) INCLUDED,
  * ![relative to containing markdown - in repo up one](../relative_to_containing_markdown_up_one.jpg) INCLUDED,

* content_line: relative to containing markdown - in repo up two](../../relative_to_containing_markdown_up_two.jpg) INCLUDED,
  * ![relative to containing markdown - in repo up two](../../relative_to_containing_markdown_up_two.jpg) INCLUDED,

* content_line: relative to containing markdown - up past root](../../../../relative_to_containing_markdown_up_past_root.jpg) INCLUDED,
  * ![relative to containing markdown - up past root](../../../../relative_to_containing_markdown_up_past_root.jpg) INCLUDED,

* content_line: relative to containing markdown - direct wrong extension bitmap](excluded.bmp) excluded,
  * ![relative to containing markdown - direct wrong extension bitmap](excluded.bmp) excluded,

* content_line: relative to containing markdown - direct wrong extension markdown](excluded.md) excluded,
  * ![relative to containing markdown - direct wrong extension markdown](excluded.md) excluded,

* content_line: "[relative to containing markdown - direct no bang](excluded.jpg) excluded",
  * "[relative to containing markdown - direct no bang](excluded.jpg) excluded",

* content_line: relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) INCLUDED,
  * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) INCLUDED,

* content_line: relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) EXCLUDED,
  * ![relative to containing markdown - direct duplicate](relative_to_markdown_direct_duplicate.jpg) EXCLUDED,

* content_line: '![relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) EXCLUDED",
  * '![relative to containing markdown - direct duplicate2](relative_to_markdown_direct_duplicate.jpg) EXCLUDED",

* content_line: relative to containing markdown - direct with video](relative_to_markdown_direct_video.mp4) INCLUDED,
  * ![relative to containing markdown - direct with video](relative_to_markdown_direct_video.mp4) INCLUDED,

* content_line: relative to containing markdown - direct with anchor](relative_to_markdown_direct_anchor.jpg#anchor) INCLUDED,
  * ![relative to containing markdown - direct with anchor](relative_to_markdown_direct_anchor.jpg#anchor) INCLUDED,

* content_line: relative to containing markdown - direct with query parmas](relative_to_markdown_direct_query.jpg?query) INCLUDED,
  * ![relative to containing markdown - direct with query parmas](relative_to_markdown_direct_query.jpg?query) INCLUDED,

* content_line: relative to containing markdown - direct with query and anchor](relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) INCLUDED,
  * ![relative to containing markdown - direct with query and anchor](relative_to_markdown_direct_query_and_anchor.jpg?query#anchor) INCLUDED,

* content_line: relative to containing markdown - direct with anchor and query](relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) INCLUDED,
  * ![relative to containing markdown - direct with anchor and query](relative_to_markdown_direct_anchor_and_query.jpg#anchor?query) INCLUDED,

* content_line: "I am not an image tag.",
  * "I am not an image tag.",

* content_line: <img src="http://google.com" alt="tag different domain different path with protocol"> excluded,
  * <img src="http://google.com" alt="tag different domain different path with protocol"> excluded,

* content_line: <img src="http://google.com/excluded.jpg" alt="tag different domain different path with protocol with filename"> excluded,
  * <img src="http://google.com/excluded.jpg" alt="tag different domain different path with protocol with filename"> excluded,

* content_line: <img src="http://google.com/fake_org/fake_project" alt="tag different domain same path with protocol"> excluded,
  * <img src="http://google.com/fake_org/fake_project" alt="tag different domain same path with protocol"> excluded,

* content_line: <img src="http://google.com/fake_org/fake_project/excluded.jpg" alt="tag different domain same path with protocol with filename"> excluded,
  * <img src="http://google.com/fake_org/fake_project/excluded.jpg" alt="tag different domain same path with protocol with filename"> excluded,

* content_line: <img src="http://github.com" alt="tag same domain different path with protocol no filename"> excluded,
  * <img src="http://github.com" alt="tag same domain different path with protocol no filename"> excluded,

* content_line: <img src="http://github.com/excluded.jpg" alt="tag same domain different path with protocol with filename"> excluded,
  * <img src="http://github.com/excluded.jpg" alt="tag same domain different path with protocol with filename"> excluded,

* content_line: <img src="https://github.com/fake_org/fake_project" alt="tag in repo with protocol no filename"> excluded,
  * <img src="https://github.com/fake_org/fake_project" alt="tag in repo with protocol no filename"> excluded,

* content_line: <img src="https://github.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
  * <img src="https://github.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
* content_line__gitlab: <img src="https://gitlab.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
* content_line__bitbucket: <img src="https://gitlab.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/tag_in_repo_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_with_protocol_with_filename.jpg" alt="tag in repo with protocol with filename"> INCLUDED,

* content_line: <img src="file://github.com/fake_org/fake_project" alt="tag in repo with weird protocol no filename"> excluded,
  * <img src="file://github.com/fake_org/fake_project" alt="tag in repo with weird protocol no filename"> excluded,

* content_line: <img src="file://github.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
  * <img src="file://github.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
* content_line__gitlab: <img src="file://gitlab.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
  * <img src="file://gitlab.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
* content_line__bitbucket: <img src="file://gitlab.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
  * <img src="file://gitlab.com/fake_org/fake_project/tag_in_repo_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
* content_line__azure: <img src="file://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,
  * <img src="file://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_weird_protocol_with_filename.jpg" alt="in repo with weird protocol with filename"> INCLUDED,

* content_line: <img src="https://github.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
  * <img src="https://github.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
* content_line__gitlab: <img src="https://gitlab.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
* content_line__bitbucket: <img src="https://gitlab.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/path/to/tag_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain/_in_repo_with_protocol_with_filename_subfoldered.jpg" alt="in repo with protocol with filename subfoldered"> INCLUDED,

* content_line: <img src="https://github.com/fake_org/fake_project/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
  * <img src="https://github.com/fake_org/fake_project/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
* content_line__gitlab: <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
* content_line__bitbucket: <img src="https://gitlab.com/fake_org/fake_project/src/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/src/main/tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//tag_in_repo_with_protocol_with_branch_with_filename.jpg" alt="tag in repo with protocol with branch with filename"> INCLUDED,

* content_line: <img src="https://github.com/fake_org/fake_project/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
  * <img src="https://github.com/fake_org/fake_project/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
* content_line__gitlab: <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
* content_line__bitbucket: <img src="https://gitlab.com/fake_org/fake_project/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered.jpg" alt="tag in repo with protocol with branch with filename subfoldered"> INCLUDED,

* content_line: <img src="https://github.com/fake_org/fake_project/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
  * <img src="https://github.com/fake_org/fake_project/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
* content_line__gitlab: <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/-/blob/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
* content_line__bitbucket: <img src="https://gitlab.com/fake_org/fake_project/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
  * <img src="https://gitlab.com/fake_org/fake_project/src/main/path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
* content_line__azure: <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,
  * <img src="https://dev.azure.com/fake-org/fake-project/_git/fake-repo?path=%2Fmain//path/to/tag_in_repo_with_protocol_with_branch_with_filename_subfoldered_with_anchor_and_query.jpg#anchor?query=X" alt="tag in repo with protocol with branch with filename subfoldered with anchor and query"> INCLUDED,

* content_line: <img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> INCLUDED,
  * <img src="/tag_relative_to_repo_root.jpg" alt="tag relative to repo root"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_sibling.jpg" alt="tag relative to containing markdown - direct sibling"> INCLUDED,

* content_line: <img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> INCLUDED,
  * <img src="subfolder/tag_relative_to_markdown_direct_sibling_subfoldered.jpg" alt="tag relative to containing markdown - direct sibling subfoldered"> INCLUDED,

* content_line: <img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> INCLUDED,
  * <img src="../subfolder/tag_relative_to_markdown_cousin_subfoldered.jpg" alt="relative to containing markdown - cousin subfoldered (down one up one)"> INCLUDED,

* content_line: <img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> INCLUDED,
  * <img src="github.com/tag_relative_to_markdown_direct_sibling_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - direct sibling subfoldered with confusing folder name"> INCLUDED,

* content_line: <img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> INCLUDED,
  * <img src="./tag_relative_to_markdown_dot_slash.jpg" alt="tag relative to containing markdown - dot slash"> INCLUDED,

* content_line: <img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> INCLUDED,
  * <img src="./subfolder/tag_relative_to_markdown_dot_slash_subfoldered.jpg" alt="tag relative to containing markdown - dot slash subfoldered"> INCLUDED,

* content_line: <img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> INCLUDED,
  * <img src="./github.com/tag_relative_to_markdown_dot_slash_subfoldered_with_confusing_folder_name.jpg" alt="tag relative to containing markdown - dot slash subfoldered with confusing folder name"> INCLUDED,

* content_line: <img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> INCLUDED,
  * <img src="../tag_relative_to_containing_markdown_up_one.jpg" alt="tag relative to containing markdown - in repo up one"> INCLUDED,

* content_line: <img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> INCLUDED,
  * <img src="../../tag_relative_to_containing_markdown_up_two.jpg" alt="tag relative to containing markdown - in repo up two"> INCLUDED,

* content_line: <img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> INCLUDED,
  * <img src="../../../../tag_relative_to_containing_markdown_up_past_root.jpg" alt="tag relative to containing markdown - up past root"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct"> ",

* content_line: <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",
  * <img src="tag_relative_to_markdown_direct_duplicate.jpg" alt="tag relative to containing markdown - direct2"> ",

* content_line: <img src="tag_excluded.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> excluded,
  * <img src="tag_excluded.bmp" alt="tag relative to containing markdown - direct wrong extension bitmap"> excluded,

* content_line: <img src="tag_excluded.md" alt="tag relative to containing markdown - direct wrong extension markdown"> excluded,
  * <img src="tag_excluded.md" alt="tag relative to containing markdown - direct wrong extension markdown"> excluded,

* content_line: <img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_video.mp4" alt="tag relatyive sibling video"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_anchor.jpg#anchor" alt="relative to containing markdown - direct with anchor"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_query.jpg?query" alt="relative to containing markdown - direct with query params"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_query_and_anchor.jpg?query#anchor" alt="relative to containing markdown - direct with query with anchor"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_anchor_and_query.jpg#anchor?query" alt="relative to containing markdown - direct with anchor with query"> INCLUDED,

* content_line: <img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> INCLUDED,
  * <img src="tag_relative_to_markdown_direct_no_alt_text.jpg"> INCLUDED,
