---
layout: page
title: My Skills
excerpt: "A List of Skills"
comments: false
---

<h2 style="text-align: center;">frequently used Tools</h2>

<style>
    /* Added custom styles for the image container */
    .service-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        margin: 0 -10px;
    }

    /* Adjusted the width to accommodate three images in a row */
    .service-item {
        flex: 0 0 calc(33.33% - 20px);
        margin: 10px;
        text-align: center;
    }
</style>

<div class="container">
    <div class="row text-center service-container">

        <!-- GCP -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('gcp')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/gcp.jpg" alt="GCP Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>GCP</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="gcpDescription" class="hidden-description" style="display: none;">
                    GCP의 다양한 서비스를 활용하여 인프라를 구축하고 관리할 수 있습니다.
                     IAM을 이용하여 보안을 강화하고 리소스에 접근하는 권한을 제어할 수 있습니다.
                </p>
            </div>
        </div>

        <!-- Docker -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('js')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/docker.jpg" alt="Docker Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Docker</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="jsDescription" class="hidden-description" style="display: none;">
                    Docker 컨테이너 기술을 이용하여 애플리케이션을 구성하고 배포할 수 있습니다.
                </p>
            </div>
        </div>

        <!-- Kubernetes -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('kubernetes')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/ks.jpg" alt="Kubernetes Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Kubernetes</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="kubernetesDescription" class="hidden-description" style="display: none;">
                    Kubernetes 클러스터를 구성하여 애플리케이션을 배포하고 관리할 수 있습니다.
                    스케일링과 업데이트 정책을 설정하여 서비스의 안정적인 애플리케이션 배포를 수행할 수 있습니다.
                </p>
            </div>
        </div>

        <!-- Linux -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('linux')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/li.jpg" alt="Linux Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Linux</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="linuxDescription" class="hidden-description" style="display: none;">
                    Linux CLI를 이용하여 파일 및 디렉토리 관리와 소프트웨어 설치, 시스템 설정 등을 수행할 수 있습니다.
                    원격 서버에 SSH를 통해 접속하여 원격 작업을 처리할 수 있습니다. 
                </p>
            </div>
        </div>

        <!-- Terraform -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('terraform')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/te.jpg" alt="Terraform Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Terraform</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="terraformDescription" class="hidden-description" style="display: none;">
                    Terraform을 이용하여 클라우드 인프라를 배포하고 관리할 수 있습니다. 
                    원격 파일 저장소를 구성해 버전을 관리하고 변경 사항을 추적할 수 있습니다.
                </p>
            </div>
        </div>

        <!-- Visual Studio Code -->
        <div class="col-12 col-sm-6 col-md-4 mb-4 service-item" onclick="toggleDescription('vscode')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/vs.jpg" alt="VS Code Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Visual Studio Code</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="vscodeDescription" class="hidden-description" style="display: none;">
                    VS Code를 사용하여 효율적으로 코드를 작성 및 관리할 수 있습니다.
                </p>
            </div>
        </div>

    </div>
</div>

<script>
    function toggleDescription(service) {
        var description = document.getElementById(service + 'Description');
        if (description.style.display === 'none' || description.style.display === '') {
            description.style.display = 'block';
        } else {
            description.style.display = 'none';
        }
    }
</script>
<br>
<br>
<h2 style="text-align: center;">Experienced Tools</h2>

<style>
    /* Added custom styles for the second image container */
    .second-service-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        margin: 0 -10px;
    }

    /* Adjusted the width to accommodate three images in a row for the second set of icons */
    .second-service-item {
        flex: 0 0 calc(33.33% - 20px);
        margin: 10px;
        text-align: center;
    }
</style>

<!-- Second Container (New) -->
<div class="container">
    <div class="row text-center second-service-container">

        <!-- New Skill 1 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/aws.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>AWS</p></h4>
        </div>

        <!-- New Skill 2 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/ng.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>NGINX</p></h4>
        </div>

        <!-- New Skill 3 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/ap.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Apache</p></h4>
        </div>

        <!-- New Skill 4 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/jenkins.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Jenkins<br /><br /></p></h4>
        </div>

        <!-- New Skill 5 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/argocd.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>ArgoCD</p></h4>
        </div>

        <!-- New Skill 6 -->
        <div class="col-12 col-sm-4 mb-4 service-item">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/github.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>Github</p></h4>
        </div>
    </div>
</div>
