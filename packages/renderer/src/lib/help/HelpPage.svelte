<style>
.generic-link > i {
  opacity: 0;
}

.generic-link:hover > i {
  opacity: 100%;
}
</style>

<script lang="ts">
import NavPage from '../ui/NavPage.svelte';
</script>

<NavPage searchEnabled="{false}" title="Help">
  <div slot="empty" class="flex flex-col min-h-full bg-zinc-700">
    <div class="min-w-full flex-1 pt-5 px-5 pb-5 space-y-5">
      <!-- Getting Started -->
      <div class="bg-zinc-800 px-3 pt-3 pb-3 rounded-lg">
        <div class="text-lg">Getting Started</div>
        <div class="flex sm:flex-col md:flex-row py-3 md:h-24">
          <div class="sm:h-full sm:my-auto md:flex md:flex-col md:w-1/2 md:border-r-2">
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman-desktop.io/docs/intro')}"
                title="https://podman-desktop.io/docs/intro">
                Getting started<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman-desktop.io/docs/troubleshooting')}"
                title="https://podman-desktop.io/docs/troubleshooting">
                Troubleshooting guide<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
          <div class="md:flex md:flex-col md:w-1/2">
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman-desktop.io/features')}"
                title="https://podman-desktop.io/features">
                View all features<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman-desktop.io/extend')}"
                title="https://podman-desktop.io/extend">
                Extend podman desktop<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Core Podman Engine -->
      <div class="bg-zinc-800 px-3 pt-3 pb-3 rounded-lg">
        <div class="text-lg">Core Podman Engine</div>
        <div class="flex sm:flex-col md:flex-row py-3 md:h-24">
          <div class="sm:h-full sm:my-auto md:flex md:flex-col md:w-1/2 md:border-r-2">
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman.io/getting-started/')}"
                title="https://podman.io/getting-started/">
                Getting started with containers<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://docs.podman.io/en/latest/Commands.html')}"
                title="https://docs.podman.io/en/latest/Commands.html">
                View podman commands<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
          <div class="md:flex md:flex-col md:w-1/2">
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://podman.io/getting-started/installation')}"
                title="https://podman.io/getting-started/installation">
                Set up podman<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://docs.podman.io/en/latest/Tutorials.html')}"
                title="https://docs.podman.io/en/latest/Tutorials.html">
                View all tutorials<i class="fas fa-solid fa-external-link-alt ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Get in Touch -->
      <div class="bg-zinc-800 px-3 pt-3 pb-3 rounded-lg">
        <div class="text-lg">Get in Touch</div>
        <div class="flex sm:flex-col md:flex-row py-3 md:h-24">
          <div class="sm:h-full sm:my-auto md:flex md:flex-col md:w-1/2 md:border-r-2">
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => window.openExternal('https://github.com/containers/podman-desktop/issues/new/choose')}"
                title="https://github.com/containers/podman-desktop/issues/new/choose">
                Report a bug<i class="fas fa-solid fa-exclamation-triangle ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() =>
                  window.openExternal('https://github.com/containers/podman-desktop/discussions/categories/general')}"
                title="https://github.com/containers/podman-desktop/discussions/categories/general">
                Create a GitHub discussion<i class="fas fa-solid fa-exclamation-triangle ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
          <div class="md:flex md:flex-col md:w-1/2">
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline"
                on:click="{() => {
                  window.events.send('display-feedback', undefined);
                }}"
                title="Share your Feedback">
                Share your Feedback<i class="fas fa-solid fa-comment ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Communication -->
      <div class="bg-zinc-800 px-3 pt-3 pb-3 rounded-lg">
        <div class="text-lg">Communication</div>
        <div class="flex sm:flex-col md:flex-row py-3 md:h-24">
          <div class="sm:h-full sm:my-auto md:flex md:flex-col md:w-1/2 md:border-r-2 md:whitespace-nowrap md:pr-2">
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline md:text-ellipsis md:overflow-hidden"
                on:click="{() => window.openExternal('https://discordapp.com/invite/TCTB38RWpf')}"
                title="https://discordapp.com/invite/TCTB38RWpf">
                Discord: Join #general channel<i class="fas fa-solid fa-comments ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline md:text-ellipsis md:overflow-hidden"
                on:click="{() => window.openExternal('https://libera.chat')}"
                title="https://libera.chat">
                Libera.Chat: Join #podman-desktop channel<i class="fas fa-solid fa-comments ml-2" aria-hidden="true"
                ></i>
              </p>
            </div>
          </div>
          <div class="md:flex md:flex-col md:w-1/2 md:whitespace-nowrap md:pl-2">
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline md:text-ellipsis md:overflow-hidden"
                on:click="{() => window.openExternal('https://fedora.im')}"
                title="https://fedora.im">
                Matrix: Join #podman-desktop channel<i class="fas fa-solid fa-comments ml-2" aria-hidden="true"></i>
              </p>
            </div>
            <div class="sm:mt-2 md:my-auto md:text-right">
              <p
                class="generic-link text-gray-100 cursor-pointer hover:no-underline md:text-ellipsis md:overflow-hidden"
                on:click="{() => window.openExternal('https://slack.k8s.io/')}"
                title="https://slack.k8s.io/">
                Slack: Join #podman-desktop channel<i class="fas fa-solid fa-comments ml-2" aria-hidden="true"></i>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</NavPage>
