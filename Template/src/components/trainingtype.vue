<template>
  <div class="trainingtype">
    <div class="main-wrapper">
      <layout-header></layout-header>
      <layout-sidebar></layout-sidebar>
      <!-- Page Wrapper -->
      <div class="page-wrapper">
        <!-- Page Content -->
        <div class="content container-fluid">
          <!-- Page Header -->
          <div class="page-header">
            <div class="row align-items-center">
              <div class="col">
                <h3 class="page-title">Training Type</h3>
                <ul class="breadcrumb">
                  <li class="breadcrumb-item">
                    <router-link to="/index">Dashboard</router-link>
                  </li>
                  <li class="breadcrumb-item active">Training Type</li>
                </ul>
              </div>
              <div class="col-auto float-right ml-auto">
                <a href="#" class="btn add-btn" data-toggle="modal" data-target="#add_type"><i class="fa fa-plus"></i>
                  Add Type</a>
              </div>
            </div>
          </div>
          <!-- /Page Header -->
          <!----Datatable-->
          <div class="row">
            <div class="col-md-12">
              <div class="table-responsive">
                <table class="table table-striped custom-table mb-0 datatable">
                  <thead>
                    <tr>
                      <th style="width: 30px;">#</th>
                      <th>Type </th>
                      <th>Description </th>
                      <th>Status </th>
                      <th class="text-right">Action</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>1</td>
                      <td>Node Training</td>
                      <td>Lorem ipsum dollar</td>
                      <td>
                        <div class="dropdown action-label">
                          <a class="btn btn-white btn-sm btn-rounded dropdown-toggle" href="#" data-toggle="dropdown"
                            aria-expanded="false">
                            <i class="fa fa-dot-circle-o text-danger"></i> Inactive
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-success"></i> Active</a>
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-danger"></i>
                              Inactive</a>
                          </div>
                        </div>
                      </td>
                      <td class="text-right">
                        <div class="dropdown dropdown-action">
                          <a href="#" class="action-icon dropdown-toggle" data-toggle="dropdown"
                            aria-expanded="false"><i class="material-icons">more_vert</i></a>
                          <div class="dropdown-menu dropdown-menu-right">
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#edit_type"><i
                                class="fa fa-pencil m-r-5"></i> Edit</a>
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#delete_type"><i
                                class="fa fa-trash-o m-r-5"></i> Delete</a>
                          </div>
                        </div>
                      </td>
                    </tr>
                    <tr>
                      <td>2</td>
                      <td>Git Training</td>
                      <td>Lorem ipsum dollar</td>
                      <td>
                        <div class="dropdown action-label">
                          <a class="btn btn-white btn-sm btn-rounded dropdown-toggle" href="#" data-toggle="dropdown"
                            aria-expanded="false">
                            <i class="fa fa-dot-circle-o text-success"></i> Active
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-success"></i> Active</a>
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-danger"></i>
                              Inactive</a>
                          </div>
                        </div>
                      </td>
                      <td class="text-right">
                        <div class="dropdown dropdown-action">
                          <a href="#" class="action-icon dropdown-toggle" data-toggle="dropdown"
                            aria-expanded="false"><i class="material-icons">more_vert</i></a>
                          <div class="dropdown-menu dropdown-menu-right">
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#edit_type"><i
                                class="fa fa-pencil m-r-5"></i> Edit</a>
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#delete_type"><i
                                class="fa fa-trash-o m-r-5"></i> Delete</a>
                          </div>
                        </div>
                      </td>
                    </tr>
                    <tr>
                      <td>3</td>
                      <td>Swift Training</td>
                      <td>Lorem ipsum dollar</td>
                      <td>
                        <div class="dropdown action-label">
                          <a class="btn btn-white btn-sm btn-rounded dropdown-toggle" href="#" data-toggle="dropdown"
                            aria-expanded="false">
                            <i class="fa fa-dot-circle-o text-danger"></i> Inactive
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-success"></i> Active</a>
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-danger"></i>
                              Inactive</a>
                          </div>
                        </div>
                      </td>
                      <td class="text-right">
                        <div class="dropdown dropdown-action">
                          <a href="#" class="action-icon dropdown-toggle" data-toggle="dropdown"
                            aria-expanded="false"><i class="material-icons">more_vert</i></a>
                          <div class="dropdown-menu dropdown-menu-right">
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#edit_type"><i
                                class="fa fa-pencil m-r-5"></i> Edit</a>
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#delete_type"><i
                                class="fa fa-trash-o m-r-5"></i> Delete</a>
                          </div>
                        </div>
                      </td>
                    </tr>
                    <tr>
                      <td>4</td>
                      <td>Html Training</td>
                      <td>Lorem ipsum dollar</td>
                      <td>
                        <div class="dropdown action-label">
                          <a class="btn btn-white btn-sm btn-rounded dropdown-toggle" href="#" data-toggle="dropdown"
                            aria-expanded="false">
                            <i class="fa fa-dot-circle-o text-danger"></i> Inactive
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-success"></i> Active</a>
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-danger"></i>
                              Inactive</a>
                          </div>
                        </div>
                      </td>
                      <td class="text-right">
                        <div class="dropdown dropdown-action">
                          <a href="#" class="action-icon dropdown-toggle" data-toggle="dropdown"
                            aria-expanded="false"><i class="material-icons">more_vert</i></a>
                          <div class="dropdown-menu dropdown-menu-right">
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#edit_type"><i
                                class="fa fa-pencil m-r-5"></i> Edit</a>
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#delete_type"><i
                                class="fa fa-trash-o m-r-5"></i> Delete</a>
                          </div>
                        </div>
                      </td>
                    </tr>
                    <tr>
                      <td>5</td>
                      <td>Laravel Training</td>
                      <td>Lorem ipsum dollar</td>
                      <td>
                        <div class="dropdown action-label">
                          <a class="btn btn-white btn-sm btn-rounded dropdown-toggle" href="#" data-toggle="dropdown"
                            aria-expanded="false">
                            <i class="fa fa-dot-circle-o text-danger"></i> Inactive
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-success"></i> Active</a>
                            <a class="dropdown-item" href="#"><i class="fa fa-dot-circle-o text-danger"></i>
                              Inactive</a>
                          </div>
                        </div>
                      </td>
                      <td class="text-right">
                        <div class="dropdown dropdown-action">
                          <a href="#" class="action-icon dropdown-toggle" data-toggle="dropdown"
                            aria-expanded="false"><i class="material-icons">more_vert</i></a>
                          <div class="dropdown-menu dropdown-menu-right">
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#edit_type"><i
                                class="fa fa-pencil m-r-5"></i> Edit</a>
                            <a class="dropdown-item" href="#" data-toggle="modal" data-target="#delete_type"><i
                                class="fa fa-trash-o m-r-5"></i> Delete</a>
                          </div>
                        </div>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
          <!---/Datatable-->
        </div>
        <!-- /Page Content -->

        <!-- Add Training Type Modal -->
        <div id="add_type" class="modal custom-modal fade" role="dialog">
          <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title">Add New</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
              <div class="modal-body">
                <form>
                  <div class="form-group">
                    <label>Type <span class="text-danger">*</span></label>
                    <input class="form-control" type="text">
                  </div>
                  <div class="form-group">
                    <label>Description <span class="text-danger">*</span></label>
                    <textarea class="form-control" rows="4"></textarea>
                  </div>
                  <div class="form-group">
                    <label class="col-form-label">Status</label>
                    <select class="select">
                      <option>Active</option>
                      <option>Inactive</option>
                    </select>
                  </div>

                  <div class="submit-section">
                    <button class="btn btn-primary submit-btn">Submit</button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
        <!-- /Add Training Type Modal -->

        <!-- Edit Training Type Modal -->
        <div id="edit_type" class="modal custom-modal fade" role="dialog">
          <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title">Edit Type</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
              <div class="modal-body">
                <form>
                  <div class="form-group">
                    <label>Type <span class="text-danger">*</span></label>
                    <input class="form-control" type="text" value="Node Training">
                  </div>
                  <div class="form-group">
                    <label>Description <span class="text-danger">*</span></label>
                    <textarea class="form-control" rows="4">Lorem ipsum ismap</textarea>
                  </div>
                  <div class="form-group">
                    <label class="col-form-label">Status</label>
                    <select class="select">
                      <option>Active</option>
                      <option>Inactive</option>
                    </select>
                  </div>

                  <div class="submit-section">
                    <button class="btn btn-primary submit-btn">Save</button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
        <!-- /Edit Training Type Modal -->

        <!-- Delete Training Type Modal -->
        <div class="modal custom-modal fade" id="delete_type" role="dialog">
          <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content">
              <div class="modal-body">
                <div class="form-header">
                  <h3>Delete Training Type</h3>
                  <p>Are you sure want to delete?</p>
                </div>
                <div class="modal-btn delete-action">
                  <div class="row">
                    <div class="col-6">
                      <a href="javascript:void(0);" class="btn btn-primary continue-btn">Delete</a>
                    </div>
                    <div class="col-6">
                      <a href="javascript:void(0);" data-dismiss="modal" class="btn btn-primary cancel-btn">Cancel</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- /Delete Training Type Modal -->

      </div>
      <!-- /Page Wrapper -->
    </div>
  </div>
</template>
<script>
  import LayoutHeader from '@/components/layouts/Header.vue'
  import LayoutSidebar from '@/components/layouts/Sidebar.vue'
  export default {
    components: {
      LayoutHeader,
      LayoutSidebar,
    },
    mounted() {
      // Select 2
      if ($('.select').length > 0) {
        $('.select').select2({
          minimumResultsForSearch: -1,
          width: '100%'
        });
      }
      // Multiselect
      if ($('#customleave_select').length > 0) {
        $('#customleave_select').multiselect();
      }
      if ($('#edit_customleave_select').length > 0) {
        $('#edit_customleave_select').multiselect();
      }
      // Datatable

      if ($('.datatable').length > 0) {
        $('.datatable').DataTable({
          "bFilter": false,
        });
      }
      if ($('.floating').length > 0) {
        $('.floating').on('focus blur', function (e) {
          $(this).parents('.form-focus').toggleClass('focused', (e.type === 'focus' || this.value.length > 0));
        }).trigger('blur');
      }
    },
    name: 'trainingtype'
  }
</script>